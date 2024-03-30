# Automato_Tesouro

Um autômato para encontrar tesouro criado em python.

https://colab.research.google.com/drive/1phjO699zyS4QLNU47dPUGswshniTiVCw?usp=sharing

É um autômato finito deterministico, sobre Livre de Contexto.

A criação dele é em cima de um contexto de mapa de tesouro, onde cada ilha ou caverna é um estado, e para chegar até as ilhas existem as transições, sobre o alfabeto: [N,S,L,O].

 - N: Significa Norte
 - S: Significa Sul
 - L: Significa Leste
 - O: Significa Oeste

E para chegar ao estado final, que é a ilha do tesouro, é uma string ou palavra em cima do alfabeto, que é um sequência de caracteres que pertece ao alfabeto, por exemplo: SSNLOSOLO.

Este autômato possui ao todo 22 estados, também foi implementada um método de força bruta para encontrar a ilha do tesouro com a string do tamnho 9, onde gera N combinaçõe, poderia fazer
com tamanho minimos começando com número baixo até uma sequência alta, porém levaria uma quantidade de tempo e de processamento alto, pois possui outras combinaçãoes para chegar até a ilha do tesouro,
onde a palavra mais rápida a encontrar o tesouro é: SSSLLOONL, mas também pode encontrar outras opções também.

Imagem do autômato:

![MAPA jff](https://github.com/Paulo-dev2/Automato_Tesouro/assets/65676235/72fd24bb-acaa-4094-add2-a3d785046601)
