# Numeros Primos
Este é um programa Python simples que utiliza o _Crivo de Eratóstenes_ para encontrar todos os números primos até 10000. 

O Crivo de Eratóstenes é um algoritmo antigo e eficiente para encontrar números primos em um intervalo específico.

## Como funciona o Crivo de Eratóstenes
O Crivo de Eratóstenes é um algoritmo que permite identificar todos os números primos até um certo limite. Ele funciona da seguinte maneira:

* Crie uma lista de números de 2 até o limite máximo que você deseja verificar (10000, no nosso caso).
* Começando pelo primeiro número (2), marque-o como primo e elimine todos os seus múltiplos da lista.
* Mova para o próximo número não marcado na lista e repita o processo: marque-o como primo e elimine seus múltiplos.
* Continue esse processo até que você tenha verificado todos os números na lista.
  
Ao final, os números não marcados na lista serão os números primos até o limite estabelecido.

## Como usar o programa
Certifique-se de ter o Python instalado em seu sistema. Você pode executar o programa da seguinte maneira:

* Abra um terminal ou prompt de comando.
* Navegue até o diretório onde o arquivo `numeros_primos.py` está localizado.
* Execute o comando: `python numeros_primos.py`
 
O programa irá calcular e exibir todos os números primos até 10000 utilizando o Crivo de Eratóstenes.

Esse código criei para resolver o desafio do grupo [OsProgramadores](https://osprogramadores.com/) 
