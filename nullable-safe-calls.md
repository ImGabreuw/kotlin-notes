# Nullable Safe Calls

## O que é?

* O operador para executar a **Safe Calls** é ``?.``
* Geralmente são úteis em chamadas em cadeia, caso uma propriedade for ``null`` a caideia retornará ``null``
* Também pode ser usado em atribuições, ou seja, se uma das propriedades for ``null`` a atribuição não será feita.
* **Documentação**: [clique aqui](https://kotlinlang.org/docs/null-safety.html#safe-calls)

## Como usar?

* Exemplo: ``?.``
  
  ````kotlin
  val linguagem = "Kotlin"
  println(linguagem.length) // 6
  ````

* Exemplo: **Encadeamento de ``?.``**
  
  ````kotlin
  val linguagem = "Kotlin"
  println(linguagem?.substring(0. 2).?length) // 3
  ````
