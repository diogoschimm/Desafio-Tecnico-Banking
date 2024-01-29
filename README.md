# Desafio-Tecnico-Banking

Sistema bancário para gerenciamento de contas e operações financeiras de um terminal bancário (ATM)

## Requisitos

Criar um caixa eletrônico

## Backend
Criar um backend que entregue os seguintes endpoints de um caixa eletrônico em C# .NetCore:

- Uma conta contem numero, agencia e tipo (corrente, poupança)
- Deposito
  - Quem foi o Depositante
  - Qual conta destino do deposito
  - Qual o valor depositado
- Consultar Saldo
- Extrato
- Saque
  - Qual o valor sacado
- Transferencia
  - Conta destino da transferencia (sempre será no mesmo banco)
  - Qual o valor transferido

### Regras

- Uma conta poupança NÃO pode transferir para uma conta corrente
- A conta corrente tem um limite de cheque especial (por padrão R$ 300,00)
- As operações de saque não podem exceder o saldo mais o limite de cheque especial
- Cada operação em conta corrente tem um custo, a primeira operação de cada mês não tem custo, os valores são:
  - Deposito: **Grátis**
  - Saque: **R$ 4,77**
  - Transferencia: **R$ 2,25**
  - Extrato: **R$ 3,82**
  - Consultar Saldo: **R$ 1,37**
- As operações com CUSTO devem ser debitadas tendo saldo ou não


## FrontEnd

Criar a interface usando umas das seguintes tecnologias:
- ReactJS
- Asp.NET MVC
- Asp.NET WebForms

  

