# **Guia de Estudos: Fundamentos de Redes e Segurança Cibernética**

Este guia foi criado para explicar os conceitos essenciais de redes de computadores e segurança cibernética de forma **clara e progressiva**, começando com os fundamentos e avançando para tópicos mais técnicos. Cada seção inclui exemplos práticos e comparações para facilitar o aprendizado.

---

## **1. Introdução às Redes de Computadores**

### **O que é uma Rede?**
Uma **rede** é um conjunto de dispositivos (computadores, smartphones, servidores) conectados entre si para compartilhar informações.

**Exemplo:**
- **LAN (Rede Local):** Conexão entre computadores em uma empresa.
- **WAN (Rede de Longa Distância):** Internet, que conecta dispositivos globalmente.

### **Componentes Básicos de uma Rede**

| Componente       | Função Principal                          | Exemplo Prático                          |
|------------------|-------------------------------------------|------------------------------------------|
| **Roteador**     | Conecta redes diferentes (ex: Wi-Fi doméstico). | O roteador da sua casa liga seu celular à internet. |
| **Switch**       | Conecta dispositivos na mesma rede.       | Um switch em um escritório liga vários computadores. |
| **Modem**        | Transforma o sinal da internet (ISP) em dados digitais. | O modem da operadora de internet. |
| **Firewall**     | Filtra tráfego malicioso.                 | Um firewall bloqueia tentativas de invasão. |

**Por que essa tabela é útil?**  
Ela mostra como cada peça da rede funciona, desde a conexão física até a segurança.

---

## **2. Protocolos de Rede e Comunicação**

### **O que é um Protocolo?**
Um **protocolo** é um conjunto de regras que define como os dispositivos se comunicam.

### **Principais Protocolos**

| Protocolo      | Função                                     | Exemplo de Uso                           |
|----------------|--------------------------------------------|-------------------------------------------|
| **HTTP/HTTPS** | Comunicação com sites (não seguro/seguro). | `http://site.com` vs. `https://site.com` |
| **DNS**        | Traduz nomes de sites em IPs.              | "google.com" → IP do servidor.           |
| **TCP**        | Garante entrega e ordem dos dados.         | Downloads, navegação web.                |
| **UDP**        | Mais rápido, sem garantias.                | Vídeos ao vivo, jogos online.            |

**Diferença entre TCP e UDP:**
- **TCP** = "Carta registrada" (confirma recebimento).
- **UDP** = "Carta comum" (mais rápida, mas pode se perder).

---

## **3. Ataques Cibernéticos Comuns em Redes**

### **Ataques de Negação de Serviço (DoS/DDoS)**
- **O que é?** Sobrecarregar um servidor com tráfego falso até ele cair.
- **Exemplo:** Site fora do ar por acessos falsos de hackers.

| Tipo de Ataque       | Como Funciona?                          | Como se Proteger?                     |
|----------------------|------------------------------------------|---------------------------------------|
| **DoS (1 origem)**   | Um único computador ataca.              | Firewalls bloqueiam IPs suspeitos.    |
| **DDoS (múltiplas origens)** | Botnet envia múltiplos acessos.     | Mitigação com Cloudflare, etc.        |

**Botnet:** Rede de computadores infectados usada para ataques DDoS.

### **Ataques de Sniffing (Espionagem de Rede)**
- **Passivo:** Observa o tráfego (ex: Wi-Fi público).
- **Ativo:** Altera dados em trânsito (ex: site falso).

**Como se proteger?**
- Use **VPN** (criptografa o tráfego).
- Evite **Wi-Fi públicos sem senha**.

---

## **4. Segurança em Redes: Firewalls, VPNs e MFA**

### **Firewalls (Barreiras de Segurança)**

| Tipo de Firewall | Como Funciona?                        | Exemplo                     |
|------------------|----------------------------------------|-----------------------------|
| **Stateful**     | Monitora conexões ativas.             | Usado em empresas.          |
| **Stateless**    | Verifica regras fixas.                | Mais simples, menos eficaz. |

### **VPN (Rede Privada Virtual)**
- **O que faz?** Esconde IP e criptografa dados.
- **Exemplo:** Acesso bancário em Wi-Fi público com segurança.

### **Autenticação Multifator (MFA)**
- **O que é?** Exige mais de uma forma de autenticação (ex: senha + código SMS).
- **Exemplo:** Login em banco com senha e código do celular.

---

## **5. Conceitos Avançados**

### **Modelo OSI vs. TCP/IP**

| Camada (OSI)     | Função                               | Exemplo                    |
|------------------|--------------------------------------|----------------------------|
| **Aplicação**    | Interface com o usuário.             | HTTP, FTP                  |
| **Rede**         | Roteamento e endereçamento.          | IP, roteadores             |
| **Física**       | Transmissão de sinais físicos.       | Cabos, conectores          |

**Nota:** O modelo **TCP/IP** é uma simplificação prática do modelo OSI.

### **Segmentação de Rede**
- **O que é?** Dividir a rede em partes para conter danos.
- **Exemplo:** Setor financeiro isolado do restante da empresa.

---

## **6. Melhores Práticas para Proteção**

### **Para Indivíduos**
- ✅ Use **senhas fortes** e **MFA**.
- ✅ Mantenha **sistemas atualizados**.
- ✅ Use **VPN em redes públicas**.

### **Para Empresas**
- ✅ Implemente **firewalls stateful**.
- ✅ Monitore a rede com **SIEM** (ex: Splunk).
- ✅ Realize **testes de penetração** periodicamente.

---

## **Conclusão**

Este guia cobriu desde **conceitos básicos de redes** (roteadores, TCP/IP) até **ataques avançados** (DDoS, sniffing) e **medidas de segurança** (firewalls, VPN).

### **Próximos passos:**
- Pratique configurar uma **rede segura em casa**.
- Explore ferramentas como **Wireshark** para monitorar o tráfego de rede.


