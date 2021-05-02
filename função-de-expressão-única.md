# Função de expressão única

## O que é?

* É uma função que retorna uma única expressão a qual vem depois do sinal de ``=``
* **Documentação**: [clique aqui](https://kotlinlang.org/docs/functions.html#single-expression-functions)

## Como usar

### Exemplo: Função de expressão única com retorno explícito

````kotlin
fun double(x: Int): Int = x * 2
````

### Exemplo: Função de expressão única com retorno implícito

**OBS**: apenas nesse tipo de função o retorno pode ser omitido

````kotlin
fun double(x: Int) = x * 2
````
