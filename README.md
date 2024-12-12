# Java-SHA-256

Funções de hash criptográficas são operações matemáticas realizadas em dados digitais; ao comparar o hash computado (ou seja, o resultado produzido pela execução de um algoritmo de hash) com um valor de hash conhecido e esperado, uma pessoa pode determinar a integridade dos dados. Por exemplo, calcular o hash de um arquivo baixado e comparar o resultado com um hash previamente publicado pode mostrar se o download foi modificado ou adulterado. Além disso, as funções de hash criptográficas são extremamente resistentes a colisões; em outras palavras, deve ser extremamente difícil gerar o mesmo resultado de hash a partir de dois valores de entrada diferentes usando uma função de hash criptográfica.

O Algoritmo de Hash Seguro 2 (SHA-2) é um conjunto de funções de hash criptográficas projetadas pela Agência de Segurança Nacional (NSA). Ele consiste em seis algoritmos de hashing idênticos (ou seja, SHA-256, SHA-512, SHA-224, SHA-384, SHA-512/224, SHA-512/256) com um tamanho de digestão variável. O SHA-256 é um algoritmo de hashing de 256 bits (32 bytes) que pode calcular um código de hash para uma entrada de até 512 bits. Ele passa por 64 rodadas de hashing e calcula um código de hash que é um número hexadecimal de 64 dígitos.

Dada uma string,2, imprima o seu valor de hash SHA-256.
