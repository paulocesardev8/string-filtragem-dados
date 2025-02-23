### string-filtragem-dados

# Descrição - Desafio 1
Imagine que você está trabalhando em um sistema de gerenciamento de estoque que recebe dados de produtos de uma API externa. Cada produto é representado por uma string que contém seu nome, preço e a quantidade disponível em estoque. Por exemplo, a string "Laptop:1200:10;Mouse:20:0;Keyboard:50:5" indica que há 10 unidades do laptop disponíveis, 0 unidades do mouse e 5 unidades do teclado.

Seu objetivo é implementar uma função em Python que filtre apenas os produtos que têm quantidade maior que zero. A função deve então retornar uma lista de strings, onde cada string representa um produto disponível, no formato original "NOME:PRECO:QUANTIDADE".

## Entrada
A entrada deve receber uma lista de strings contendo o nome do produto, preço e a quantidade disponível em estoque, separados por “:” respectivamente.

## Saída
Deverá retornar uma lista de strings, onde cada string contém as informações dos produtos que têm quantidade maior que 0.

### Exemplos
A tabela abaixo apresenta exemplos com alguns dados de entrada e suas respectivas saídas esperadas. Certifique-se de testar seu programa com esses exemplos e com outros casos possíveis.

|Entrada |	Saída |
| ------ | ------- |
| Laptop:1200:10;Mouse:20:0;Keyboard:50:5 |	['Laptop:1200:10', 'Keyboard:50:5']|
| Monitor:300:0;Pen:2:100	| ['Pen:2:100']|
| Tablet:150:15;Chair:85:0 |	['Tablet:150:15'] |


# Desafio 2 - Descrição
Você está consumindo dados de uma API de uma instituição financeira que fornece uma lista de transações. Seu desafio é filtrar todas as transações que possuem um valor acima de um determinado limite.

## Entrada
A entrada deve receber dois valores:
1. Um número decimal representando o valor limite.
2. Uma string contendo transações no seguinte formato: "ID:VALOR;ID:VALOR;..."

## Saída
Deverá retornar uma lista de strings, onde cada string contém as informações das transações cujo valor é maior que o valor limite especificado.

### Exemplos
A tabela abaixo apresenta exemplos com alguns dados de entrada e suas respectivas saídas esperadas. Certifique-se de testar seu programa com esses exemplos e com outros casos possíveis.

| Entrada |	Saída |
|---------|---------|
|150.00 1:100.00;2:200.50;3:150.75 |	['2:200.5', '3:150.75']|
|300.00 4:500.00;5:600.00	| ['4:500.0', '5:600.0']|
|100.00 6:250.25;7:90.00;8:110.50	| ['6:250.25', '8:110.5']|
