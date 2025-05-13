# Guia de Estudos: Introdução à Segurança Cibernética e Resposta a Incidentes  

Este guia foi criado para ajudar você a entender os conceitos básicos de segurança cibernética e resposta a incidentes, apresentados no glossário do curso. Vamos organizar os tópicos em uma sequência lógica, começando pelos fundamentos e avançando para temas mais complexos. Cada seção inclui explicações simples, exemplos práticos e tabelas comparativas para facilitar o aprendizado.  

---  

## 1. Conceitos Básicos de Segurança Cibernética  

### **O que é um Incidente de Segurança?**  
Um incidente de segurança é qualquer evento que possa prejudicar a confidencialidade, integridade ou disponibilidade de informações ou sistemas. Por exemplo, se um vírus infecta um computador e apaga arquivos importantes, isso é um incidente.  

### **Detecção de Ameaças**  
- **Análise de Ameaças:** Investigar alertas para determinar se são reais.  
  - *Exemplo:* Um sistema alerta sobre um login suspeito. A equipe verifica se foi um erro ou um ataque.  
- **Indicadores de Compromisso (IoC):** Sinais que sugerem um possível incidente.  
  - *Exemplo:* Tráfego incomum de dados para um servidor desconhecido.  
- **Indicadores de Ataque (IoA):** Sequência de eventos que indicam um ataque em andamento.  
  - *Exemplo:* Várias tentativas de login falhas seguidas por um acesso bem-sucedido.  

#### Tabela Comparativa: IoC vs. IoA  
| **Indicadores de Compromisso (IoC)** | **Indicadores de Ataque (IoA)** |  
|--------------------------------------|----------------------------------|  
| Sinais de que algo ruim pode ter acontecido. | Sinais de que um ataque está ocorrendo agora. |  
| Exemplo: Arquivo suspeito encontrado. | Exemplo: Tentativas repetidas de invadir um sistema. |  

*Esta tabela ajuda a diferenciar entre sinais de um possível problema (IoC) e sinais de um ataque em curso (IoA).*  

---  

## 2. Ferramentas e Sistemas de Monitoramento  

### **Sistemas de Detecção e Prevenção**  
- **IDS (Sistema de Detecção de Intrusões):** Monitora atividades e alerta sobre possíveis invasões.  
  - *Exemplo:* Um IDS avisa quando alguém tenta acessar um sistema sem permissão.  
- **IPS (Sistema de Prevenção de Intrusões):** Além de detectar, tenta bloquear o ataque.  
  - *Exemplo:* Um IPS impede que um hacker explore uma vulnerabilidade no sistema.  

#### Tabela Comparativa: IDS vs. IPS  
| **IDS**                                | **IPS**                                |  
|----------------------------------------|----------------------------------------|  
| Apenas detecta e alerta sobre ameaças. | Detecta e tenta bloquear ameaças.      |  
| Exemplo: Alarme de incêndio.           | Exemplo: Alarme que também apaga o fogo. |  

*Essa tabela mostra a diferença entre ferramentas que só avisam (IDS) e as que também agem (IPS).*  

### **SIEM e SOAR**  
- **SIEM (Segurança e Gerenciamento de Eventos):** Coleta e analisa dados de logs para identificar ameaças.  
  - *Exemplo:* Um SIEM correlaciona logs de vários sistemas para detectar um ataque coordenado.  
- **SOAR (Resposta Automatizada):** Usa automação para responder a ameaças rapidamente.  
  - *Exemplo:* Um SOAR pode isolar automaticamente um computador infectado.  

---  

## 3. Resposta a Incidentes  

### **Ciclo de Vida de Resposta a Incidentes (NIST)**  
1. **Preparação:** Ter um plano e ferramentas prontas.  
2. **Detecção e Análise:** Identificar e investigar alertas.  
3. **Contenção, Erradicação e Recuperação:**  
   - *Contenção:* Isolar o problema para evitar mais danos.  
   - *Erradicação:* Remover completamente a ameaça.  
   - *Recuperação:* Restaurar sistemas afetados.  
4. **Pós-Incidente:** Aprender com o ocorrido para melhorar.  

### **Exemplo Prático**  
*Cenário:* Um ransomware criptografa arquivos em uma empresa.  
1. **Detecção:** O SIEM alerta sobre atividade suspeita.  
2. **Contenção:** Desconectar os sistemas infectados da rede.  
3. **Erradicação:** Remover o ransomware dos computadores.  
4. **Recuperação:** Restaurar arquivos a partir de backups.  
5. **Pós-Incidente:** Revisar como o ataque aconteceu e melhorar as defesas.  

---  

## 4. Conceitos Avançados  

### **Inteligência de Ameaças**  
- **Open-Source Intelligence (OSINT):** Coletar informações de fontes públicas.  
  - *Exemplo:* Analisar posts em fóruns para identificar novas ameaças.  
- **Threat Hunting:** Busca proativa por ameaças antes que causem danos.  
  - *Exemplo:* Procurar por comportamentos incomuns na rede.  

### **Ferramentas Úteis**  
- **Wireshark:** Analisa tráfego de rede.  
- **VirusTotal:** Verifica arquivos suspeitos.  
- **Honeypot:** Sistema "isco" para atrair hackers e estudar seus métodos.  

---  

## 5. Boas Práticas e Documentação  

### **Plano de Continuidade de Negócios (BCP)**  
Um documento que descreve como manter as operações durante um desastre.  
- *Exemplo:* Se um ataque derrubar os servidores, o BCP define como continuar trabalhando.  

### **Lições Aprendidas**  
Reuniões após um incidente para discutir o que deu certo e o que pode ser melhorado.  

---  

## Conclusão  
Este guia abordou desde conceitos básicos, como detecção de ameaças, até tópicos avançados, como resposta a incidentes e inteligência de ameaças. Use as tabelas comparativas para fixar as diferenças entre termos semelhantes e os exemplos práticos para entender como os conceitos se aplicam no mundo real. Com prática e estudo, você estará melhor preparado para entender e atuar na área de segurança cibernética!