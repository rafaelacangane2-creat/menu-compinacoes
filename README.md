# Calculadora de Análise Combinatória em C

Programa em C com menu interativo que permite ao usuário escolher entre quatro operações de análise combinatória, usando a estrutura `switch case`.

## Funcionalidades

**Triângulo de Pascal**: imprime o triângulo com o número de linhas escolhido.
**Arranjo simples**: calcula A(n, p) = n! / (n - p)!
**Permutação simples**: calcula P(n) = n!
**Combinação simples**: calcula C(n, p) = n! / (p! · (n - p)!)

## Observações

- Os valores de `n` e `p` devem ser inteiros, com `0 <= p <= n <= 12`.
- O limite de 12 existe porque 13! ultrapassa o maior valor que cabe em um `int` de 32 bits.
- O triângulo de Pascal utiliza a função de combinação para calcular cada elemento.

## Conceitos utilizados

- Estruturas de repetição (`for`, `do while`)
- Estrutura condicional (`if`, `switch case`)
- Funções
- Entrada e saída com `scanf` e `printf`

## Autora
Rafaela das Neves Cangane

