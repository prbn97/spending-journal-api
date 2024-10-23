# Spending Diary 
A spending journal is API to record of your daily money transactions to pass through your mouth.

## Estrutura do Spending Diary
O spending diary será uma estrutura que o usuário cria mensalmente. Dentro desse diário, teremos três categorias de despesas:

- Despesas fixas: 
> São aquelas recorrentes, como aluguel ou contas de serviços.
- Despesas genéricas: 
> Despesas variadas que podem mudar de mês para mês, como compras e lazer.
- Despesas de crédito: 
> Gastos no cartão de crédito, que podem ser detalhados conforme o usuário desejar.

![expensesTypes](/src/expensesTypes.jpeg)

### Despesas Fixas e Genéricas
As despesas fixas e genéricas têm estruturas simples e diretas, ambas baseadas em uma lista de despesas com um valor total

despesas possuem 3 principais partes:
> o nome/tipo da despesa

> o arry de despesas

> o valor somado de cada as despesa do arry

![expenses](/src/expenses-struct.jpeg)

### Despesas de Crédito
A estrutura de despesas de crédito também começa simples, mas pode evoluir para um nível mais detalhado conforme o usuário quiser

![credit-expenses](/src/credit-expenses-simpleXdetailed.jpeg)

#### Despesas de Crédito Simples
O usuário registra somente o valor total das despesas no cartão.

#### Despesas de Crédito Detalhadas 
Se o usuário quiser detalhar as faturas do cartão, como parcelamentos e o limite disponível, essa estrutura pode ser ativada dentro da estrutura Despesas de Crédito7777.