# Sistema_Bancario_POO_v1
Esse código representa um modelo orientado a objetos para um sistema bancário simples. Ele permite a realização de transações básicas como depósitos, saques e consulta de extrato, além de incluir funcionalidades de registro de transações, cadastro de usuários e contas.

## 📚 Funcionalidades

- Cadastro de clientes (Pessoa Física)
- Criação de contas correntes
- Realização de saques e depósitos
- Controle de limite de saques e valores
- Histórico de transações com data e hora
- Registro automático de todas as transações

## 🧱 Estrutura de Classes

- `Cliente`: Classe base para clientes, com endereço e contas.
- `PessoaFisica`: Herda de `Cliente`, representa clientes PF com nome, CPF e data de nascimento.
- `Conta`: Representa uma conta genérica com saldo, número, agência e histórico.
- `ContaCorrente`: Herda de `Conta`, adiciona limite de saque e quantidade máxima de saques.
- `Historico`: Registra todas as transações realizadas.
- `Transacao`: Classe abstrata para operações financeiras.
  - `Saque`: Implementa operação de saque.
  - `Deposito`: Implementa operação de depósito.
