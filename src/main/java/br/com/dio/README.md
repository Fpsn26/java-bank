# Java-Bank

Aplicação desenvolvida em Java com o objetivo de consolidar conceitos fundamentais da **Programação Orientada a Objetos (POO)**, como **herança, encapsulamento, polimorfismo, abstração e reuso de código**.  

O sistema simula um **banco digital** básico, oferecendo funcionalidades como criação de contas, depósitos, saques, transferências via PIX, criação de investimentos e acompanhamento do histórico de transações.

---

## 🎯 Objetivo
Consolidar conceitos de POO em Java por meio da prática, aplicando-os em um projeto que simula operações bancárias do dia a dia.

---

## 🚀 Funcionalidades
- Criar contas bancárias  
- Realizar depósitos e saques  
- Transferências via PIX entre contas  
- Criar e gerenciar investimentos  
- Sacar valores investidos  
- Listar contas, investimentos e carteiras de investimentos  
- Atualizar automaticamente os investimentos  
- Consultar histórico detalhado de transações  

Menu interativo exibido no terminal:
```
1 - Criar uma conta
2 - Criar um investimento
3 - Fazer um investimento
4 - Depositar na conta
5 - Sacar da conta
6 - Transferência entre contas
7 - Investir
8 - Sacar investimento
9 - Listar contas
10 - Listar investimentos
11 - Listar carteiras de investimentos
12 - Atualizar investimentos
13 - Histórico da conta
14 - Sair
```

---

## 🛠️ Tecnologias Utilizadas
- **Java 23**
- **Gradle** (build e gerenciamento do projeto)

---

## ▶️ Como Executar
### Pré-requisitos
- Java 23 instalado  
- Gradle configurado (ou use o wrapper incluso)

### Passos
1. Clone o repositório:
   ```bash
   git clone https://github.com/Fpsn26/java-bank.git
   cd java-bank
   ```
2. Compile e execute a aplicação:
   ```bash
   ./gradlew build
   java -cp build/classes/java/main br.com.dio.main.Main
   ```

---

## 📂 Estrutura do Projeto
```
src/
 └── main/
     └── java/
         └── br/com/dio/
             ├── exception/     # Tratamento de exceções personalizadas
             ├── model/         # Classes de domínio (Conta, Cliente, Investimento, etc.)
             ├── repository/    # Repositórios em memória para simular persistência
             └── Main          # Classe Main com fluxo interativo do sistema
```

---

## 💻 Exemplo de Uso
```
1 - Criar uma conta
Informe as chaves pix (separadas por ';'): 1234567890
Informe o valor inicial de deposito: 1000
Conta criada

4 - Depositar na conta
Informe a chave pix da conta para depósito: 1234567890
Informe o valor que será depositado: 500
```

---

## 📘 Aprendizados
Durante o desenvolvimento deste projeto, foram trabalhados os seguintes conceitos:
- Estruturação de entidades utilizando **herança e composição**
- Encapsulamento de regras de negócio em serviços e repositórios
- **Polimorfismo** aplicado em diferentes tipos de conta e investimento
- Uso de **abstrações** para generalizar comportamentos
- Reuso de código por meio de boas práticas de POO
- Interação com o usuário via **menus de console**
- Organização do código em pacotes para maior clareza e manutenibilidade

---

## 📌 Status do Projeto
📚 Projeto de estudo pessoal – não está aberto a contribuições externas.
