# Guia de Estudos: Introdução à Programação em Python  

Este guia foi criado para ajudar você a entender os conceitos básicos de programação em Python, apresentados no glossário do curso. Vamos organizar os tópicos em uma sequência lógica, começando pelos fundamentos e avançando para temas mais complexos. Cada seção inclui explicações simples, exemplos práticos e tabelas comparativas para facilitar o aprendizado.  

---  

## 1. Fundamentos da Programação em Python  

### **O que é Python?**  
Python é uma linguagem de programação usada para criar instruções que o computador pode executar. Ela é conhecida por ser fácil de aprender e ler, sendo ideal para iniciantes.  

### **Elementos Básicos**  
- **Variável:** Um "recipiente" que armazena dados.  
  - *Exemplo:* `idade = 25` (a variável `idade` guarda o valor `25`).  
- **Tipos de Dados:** Categorias de informações que podem ser usadas.  
  - *Exemplo:* Números (`10`), textos (`"Olá"`), valores lógicos (`True` ou `False`).  

#### Tabela Comparativa: Tipos de Dados Comuns  
| **Tipo de Dado**  | **Descrição**                          | **Exemplo**        |  
|--------------------|----------------------------------------|--------------------|  
| `int` (inteiro)   | Números sem decimais.                  | `42`               |  
| `float`           | Números com decimais.                  | `3.14`             |  
| `str` (string)    | Texto.                                 | `"Python"`         |  
| `bool` (booleano) | Valor lógico (`True` ou `False`).      | `True`             |  

*Esta tabela ajuda a identificar os tipos de dados mais usados em Python.*  

---  

## 2. Estruturas de Controle e Funções  

### **Tomada de Decisões**  
- **Condicional (`if`):** Executa um bloco de código se uma condição for verdadeira.  
  - *Exemplo:*  
    ```python
    if idade >= 18:
        print("Maior de idade")
    else:
        print("Menor de idade")
    ```  

### **Repetição (`for` e `while`)**  
- **Loop `for`:** Repete um bloco para cada item em uma lista.  
  - *Exemplo:*  
    ```python
    for numero in [1, 2, 3]:
        print(numero)
    ```  
- **Loop `while`:** Repete um bloco enquanto uma condição for verdadeira.  
  - *Exemplo:*  
    ```python
    contador = 0
    while contador < 3:
        print(contador)
        contador += 1
    ```  

### **Funções**  
- **Função:** Um bloco de código reutilizável.  
  - *Exemplo:*  
    ```python
    def saudacao(nome):
        return f"Olá, {nome}!"
    print(saudacao("Ana"))  # Saída: "Olá, Ana!"
    ```  

#### Tabela Comparativa: `for` vs. `while`  
| **Loop `for`**                          | **Loop `while`**                          |  
|-----------------------------------------|-------------------------------------------|  
| Usado quando sabemos quantas vezes repetir. | Usado quando não sabemos quantas vezes repetir. |  
| *Exemplo:* Iterar sobre uma lista.      | *Exemplo:* Repetir até que o usuário digite "sair". |  

*Essa tabela mostra quando usar cada tipo de loop.*  

---  

## 3. Estruturas de Dados em Python  

### **Listas**  
- **Lista:** Coleção ordenada e mutável de itens.  
  - *Exemplo:* `frutas = ["maçã", "banana", "laranja"]`  

### **Dicionários**  
- **Dicionário:** Armazena pares de chave-valor.  
  - *Exemplo:*  
    ```python
    pessoa = {"nome": "Carlos", "idade": 30}
    print(pessoa["nome"])  # Saída: "Carlos"
    ```  

### **Tuplas e Conjuntos**  
- **Tupla:** Coleção ordenada e imutável.  
  - *Exemplo:* `coordenadas = (10, 20)`  
- **Conjunto (`set`):** Coleção não ordenada de itens únicos.  
  - *Exemplo:* `numeros = {1, 2, 3}`  

#### Tabela Comparativa: Estruturas de Dados  
| **Estrutura** | **Ordenada?** | **Mutável?** | **Itens Únicos?** | **Exemplo**          |  
|---------------|---------------|--------------|--------------------|----------------------|  
| Lista         | Sim           | Sim          | Não                | `[1, 2, 3]`          |  
| Dicionário    | Não           | Sim          | Chaves únicas      | `{"chave": "valor"}` |  
| Tupla         | Sim           | Não          | Não                | `(1, 2, 3)`          |  
| Conjunto      | Não           | Sim          | Sim                | `{1, 2, 3}`          |  

*Esta tabela resume as diferenças entre as principais estruturas de dados.*  

---  

## 4. Ferramentas e Boas Práticas  

### **Ambiente de Desenvolvimento (IDE)**  
- **IDE:** Software que ajuda a escrever, testar e depurar código.  
  - *Exemplo:* VS Code, PyCharm.  

### **Depuração (`debugging`)**  
- **Debugging:** Processo de encontrar e corrigir erros no código.  
  - *Exemplo:* Usar o `print()` para verificar valores de variáveis.  

### **Boas Práticas**  
- **Comentários:** Explicam o código para outros programadores.  
  - *Exemplo:* `# Calcula a média` antes de um cálculo.  
- **PEP 8:** Guia de estilo para escrever código Python claro.  
  - *Exemplo:* Usar `snake_case` para nomes de variáveis (`minha_variavel`).  

---  

## 5. Tópicos Avançados (Opcional)  

### **Módulos e Bibliotecas**  
- **Módulo:** Arquivo com funções reutilizáveis.  
  - *Exemplo:* `math` (para cálculos matemáticos).  
- **Biblioteca:** Coleção de módulos.  
  - *Exemplo:* `pandas` (para análise de dados).  

### **Expressões Regulares (`regex`)**  
- **Regex:** Padrões para buscar texto.  
  - *Exemplo:* Validar um e-mail com `r"\w+@\w+\.com"`.  

---  

## Conclusão  
Este guia abordou desde conceitos básicos, como variáveis e loops, até estruturas de dados e boas práticas. Use as tabelas para comparar estruturas ou loops, e os exemplos para praticar. Com tempo e prática, você estará pronto para criar seus próprios programas em Python!  

**Dica final:** Experimente escrever pequenos programas para fixar os conceitos, como uma calculadora ou uma lista de tarefas.