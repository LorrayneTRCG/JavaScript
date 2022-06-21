# Orientação a Objetos

Este repositório contém a atividade prática do Curso "Orientação a Objetos".

## Atividade: Conta Bancária

Nesta atividade, foram testdosr os conceitos de Orientação a Objetos simulando a criação de diversos tipos de contas bancárias e operações disponíveis em cada uma.

(X) Criar a classe `ContaBancaria`, que possui os parâmetros `agencia`, `numero`, `tipo` e `saldo`;

(X) Dentro de `ContaBancaria`, construir o getter e o setter de `saldo`;

(X) Dentro de `ContaBancaria`, criar os métodos `sacar` e `depositar`;

(X) Criar uma classe-filha chamada `ContaCorrente` que herda todos esses parâmetros e ainda possua o parâmetro `cartaoCredito`;

(X) Ainda em `ContaCorrente`, construir o getter e o setter de `cartaoCredito`;

(X) Ainda em `ContaCorrente`, fazer com que o `tipo` seja 'conta corrente' por padrão;

(X) Criar uma classe-filha chamada `ContaPoupanca` que herda todos os parâmetros de `ContaBancaria`;

(X) Criar uma classe-filha chamada `ContaUniversitaria` que herda todos os parâmetros de `ContaBancaria`;

(X) Fazer com que o método `saque` de `ContaUniversitaria` apenas seja capaz de sacar valores **menores que 500 reais**.