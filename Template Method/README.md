# Template Method

## Classification
Comportamental de Classes
 
## Intent
O Template Method é um padrão de projeto que forma o esqueleto de um algoritmo na superclasse mas deixa as subclasses sobrescreverem etapas específicas do algoritmo, tudo isso sem modificar a estrutura do algoritmo em questão.

## Motivation
Por exemplo, imagine que existe um usuário que tenta extrair de um programa arquivos/documentos escritos em programas diferentes, DOC, PDF e assim por diante. Nesse programa, é possível notar que o código desses arquivos se assemelham demais, no entanto, sabemos que tratam-se de arquivos muito distintos. Dessa forma, o padrão em questão quebra um algoritimo em várias partes, e essas partes se tormnam métodos e série de chamadas são feitas dentro de um único método padrão.

## Applicability
Usado para implementar partes inváriaveis de um algoritmo e assim, deixar que subclasses implementem corportamentos váriaveis. Usado também para tentar controlar o tamanho de determinadas subclasses.
Evitar duplicação do código colocando comportamentos comuns entre as subclasses em uma subclasse comum.

## Structure 
Na estrutura desse métodos temos:
--Classe concretas: que tem o direito de sobrescrever todas as etapas, no entanto, não podem sobrescrever o próprio método padrão 
--Classe Abstrat: Chama alguns métodos que vão funcionar como etapas de um algoritmo.

imagem

## Participants

## Sample code 