# Guia de Estudos: Gestão de Riscos e Estruturas de Segurança  

Este guia foi criado para explicar os conceitos essenciais de gestão de riscos e estruturas de segurança de forma clara e progressiva. Vamos começar com os fundamentos e avançar para tópicos mais avançados, sempre com exemplos práticos e linguagem acessível.  

---

## 1. Fundamentos da Gestão de Riscos  

### O que é Risco em Segurança da Informação?  
Risco é qualquer coisa que possa prejudicar a **confidencialidade**, **integridade** ou **disponibilidade** de um ativo (como dados, sistemas ou redes).  

**Exemplo:** Um vírus (malware) que apaga arquivos importantes representa um risco à **integridade** dos dados.  

### A Tríade CIA: Relembrando  

| Conceito             | Impacto do Risco                            | Exemplo de Ameaça                                       |
|----------------------|---------------------------------------------|----------------------------------------------------------|
| **Confidencialidade**| Dados são acessados por pessoas não autorizadas. | Um hacker rouba senhas de clientes.                   |
| **Integridade**      | Dados são alterados ou corrompidos.         | Um funcionário edita registros financeiros sem permissão.|
| **Disponibilidade**  | Dados/sistemas ficam inacessíveis.          | Um ataque de ransomware bloqueia o acesso a arquivos.   |

**Por que essa tabela é útil?**  
Ela ajuda a entender como os riscos afetam cada parte da segurança. Por exemplo, um ataque de ransomware prejudica a **disponibilidade** (bloqueia acesso) e a **integridade** (pode criptografar dados).  

---

## 2. O Framework NIST e Seus Passos  

O **NIST Cybersecurity Framework (CSF)** é um guia voluntário usado por organizações para gerenciar riscos. Ele possui **7 etapas** no **NIST RMF (Risk Management Framework)**:  

| Etapa do NIST RMF | O que Significa?                       | Exemplo Prático                                               |
|-------------------|----------------------------------------|----------------------------------------------------------------|
| **1. Preparar**    | Planejar antes de agir.                | Criar políticas de segurança para a empresa.                   |
| **2. Categorizar** | Classificar riscos e ativos.           | Listar quais dados são mais críticos (ex: informações de clientes). |
| **3. Selecionar**  | Escolher controles de segurança.       | Instalar firewalls e antivírus.                                |
| **4. Implementar** | Colocar os controles em prática.       | Treinar funcionários para usar senhas fortes.                  |
| **5. Avaliar**     | Verificar se os controles funcionam.   | Testar se o firewall bloqueia ataques.                         |
| **6. Autorizar**   | Aprovar os sistemas como seguros.      | A equipe de TI confirma que os dados estão protegidos.         |
| **7. Monitorar**   | Acompanhar continuamente.              | Usar ferramentas como **SIEM** para detectar ameaças em tempo real. |

**Por que essa tabela é útil?**  
Ela mostra o ciclo completo de gestão de riscos, desde o planejamento até a manutenção. Por exemplo, uma empresa que segue essas etapas estará melhor preparada contra ataques.  

---

## 3. Ameaças Internas vs. Externas  

### Ameaças Externas  
- **O que são?** Riscos que vêm de fora da organização (hackers, vírus, phishing).  
- **Exemplo:** Um cibercriminoso envia e-mails falsos para roubar dados.  

### Ameaças Internas  
- **O que são?** Riscos causados por funcionários, voluntários ou parceiros.  
- **Exemplo:** Um ex-funcionário vaza informações confidenciais por vingança.  

| Tipo de Ameaça   | Como Acontece?                           | Como Prevenir?                                    |
|------------------|-------------------------------------------|---------------------------------------------------|
| **Externa**      | Ataques de hackers, malware, phishing.    | Usar firewalls, antivírus e treinamento.          |
| **Interna**      | Erros humanos ou ações maliciosas.        | Limitar acessos e monitorar atividades.           |

**Por que essa tabela é útil?**  
Ela destaca que a segurança não é só sobre hackers externos; funcionários também podem ser riscos (sem querer ou intencionalmente).  

---

## 4. Ferramentas e Técnicas de Proteção  

### Controles de Segurança  
- **Autenticação:** Verificar identidades (ex: senhas, biometria).  
- **Criptografia:** Codificar dados para que só autorizados leiam.  
- **SIEM (Security Information and Event Management):** Ferramenta que monitora ameaças em tempo real.  

**Exemplo:** Um banco usa **biometria** (impressão digital) para autenticar clientes no aplicativo.  

### Resposta a Incidentes  
- **O que é?** Agir rápido para conter um ataque e minimizar danos.  
- **Passos:**  
  1. **Identificar** o problema (ex: rede lenta pode ser um vírus).  
  2. **Conter** o dano (isolar sistemas infectados).  
  3. **Corrigir** (remover malware e restaurar backups).  

---

## 5. Conceitos Avançados  

### Ransomware  
- **O que é?** Malware que bloqueia dados e exige pagamento para liberá-los.  
- **Como se proteger?** Backups frequentes e não pagar resgates.  

### Responsabilidade Compartilhada  
- **O que significa?** Todos na organização (não só o TI) devem proteger dados.  
- **Exemplo:** Funcionários evitam clicar em links suspeitos de e-mails.  

---

## 6. Melhores Práticas para Organizações  

### Usar Frameworks  
- **NIST CSF:** Para gerenciar riscos.  
- **OWASP:** Para segurança de aplicativos.  

### Treinamento Contínuo  
- Ensine equipes a identificar phishing e usar senhas seguras.  

---

## Conclusão  

Este guia cobriu desde a base (Tríade CIA, NIST RMF) até ameaças complexas (ransomware, ameaças internas). Lembre-se:  
- **Gestão de riscos é um processo contínuo.**  
- **Ferramentas como SIEM e criptografia são essenciais.**  
- **Todos na empresa têm papel na segurança.**  

**Próximos passos:** Explore ferramentas como **Splunk** (para análise de logs) e pratique planos de resposta a incidentes!
