# Sistema_Bancario_POO_v1
Esse código representa um modelo orientado a objetos para um sistema bancário simples. Ele permite a realização de transações básicas como depósitos, saques e consulta de extrato, além de incluir funcionalidades de registro de transações, cadastro de usuários e contas.
O sistema possui um menu interativo com as seguintes opções:

Criar Usuário:
Permite cadastrar um novo usuário informando nome, CPF, data de nascimento e endereço.

Criar Conta Corrente:
Associa uma nova conta a um usuário já existente (identificado pelo CPF). Cada conta tem número, agência e CPF do titular.

Depositar:
Adiciona um valor positivo ao saldo da conta. Valor deve ser maior que zero.

Sacar:
Permite saques respeitando as seguintes regras:

Limite de R$500 por operação;

Limite de 3 saques diários;

Deve haver saldo suficiente na conta.

Extrato:
Exibe o saldo atual e o histórico completo de transações (depósitos e saques).

Listar Contas:
Mostra todas as contas cadastradas, com seus respectivos titulares.

Sair:
Encerra o programa.
