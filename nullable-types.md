# Nullable Types

## O que é?

* Kotlin é uma liguagem considerada null safety, ou seja, visa eliminar os NPEs (``NullPointerException``)
* **Documentação**: [clique aqui](https://kotlinlang.org/docs/null-safety.html#nullable-types-and-non-null-types)

### Fatores que podem causar NPE

* Chamada explícita para ``throw NullPointerException()``
* Uso do operador ``!!``
* Inconsistência de dados em relação à inicialização

## Como usar?

* Exemplo: **declaração de variáveis null safety**

````kotlin
var nome: String = "Gabriel"
nome = null // Erro de compilação
````

* Exemplo: **declaração de variáveis que aceitam valor ``null``**

````kotlin
var nome: String? = "Gabriel"
nome = null // ✔
````
