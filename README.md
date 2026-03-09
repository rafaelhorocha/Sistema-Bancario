#  Sistema Bancário em Python

![Python](https://img.shields.io/badge/Python-3.10%2B-blue)  


Um sistema bancário orientado a objetos desenvolvido em **Python**, com suporte a clientes, contas correntes, depósitos, saques e histórico de transações.  
O projeto foi construído com foco em **boas práticas de programação**, aplicando conceitos de **abstração, herança e polimorfismo**.

---

##  Recursos Principais

-  **Gerenciamento de clientes** (Pessoa Física)  
-  **Criação de contas correntes** vinculadas a clientes  
-  **Depósitos** com validação de valores  
-  **Saques** com controle de limite e quantidade máxima de operações  
-  **Histórico de transações** detalhado com data e tipo de operação  
-  Estrutura modular e extensível para futuras melhorias  

---

## 🏗️ Arquitetura

| Classe            | Função |
|-------------------|--------|
| **Cliente**       | Representa um cliente genérico, com endereço e contas |
| **PessoaFisica**  | Especialização de Cliente, com nome, CPF e data de nascimento |
| **Conta**         | Modelo de conta bancária, com saldo, número, agência e histórico |
| **ContaCorrente** | Extensão de Conta, com limite de saque e limite de operações |
| **Historico**     | Armazena todas as transações realizadas em uma conta |
| **Transacao (ABC)** | Classe abstrata para operações financeiras |
| **Saque**         | Implementa a operação de saque |
| **Deposito**      | Implementa a operação de depósito |

---

##  Tecnologias

- **Python 3.10+**  
- Módulos padrão: `abc`, `datetime`  
- Paradigma: **Programação Orientada a Objetos**

---

##  Desenvolvido por:
- Rafael Henrique Oliveira Rocha
