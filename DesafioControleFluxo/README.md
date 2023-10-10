# Desafio Controle de Fluxo em Java

Este é um projeto de exemplo para demonstrar o uso de controle de fluxo em Java. A aplicação recebe dois parâmetros via terminal que representam dois números inteiros e realiza a impressão desses números em um loop `for`.

## Cenário

O sistema realiza as seguintes ações:

1. Recebe dois números inteiros como parâmetros via terminal.
2. Calcula a quantidade de interações necessárias para imprimir os números no console, incrementando a partir do primeiro número até o segundo número.
3. Se o primeiro parâmetro for MAIOR que o segundo parâmetro, uma exceção customizada chamada `ParametrosInvalidosException` será lançada com a mensagem "O segundo parâmetro deve ser maior que o primeiro".

## Funcionamento

Se o programa rodar sem nenhuma exceção, ele realizará o loop `for` com o cálculo da contagem, imprimindo os números no console.

## Exceção Customizada

A exceção customizada `ParametrosInvalidosException` será lançada se o primeiro parâmetro for MAIOR que o segundo parâmetro, com a mensagem "O segundo parâmetro deve ser maior que o primeiro".
