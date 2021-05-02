# Operador Elvis

## O que é?

* Operador elvis = ``?:``
* **Documentação**: [clique aqui](https://kotlinlang.org/docs/null-safety.html#elvis-operator)

## Como usar?

* Se a expressão à esquerda de ``?:`` não for ``null``, o operador elvis o retorna, caso contrário, ele retorna a expressão à direita. 

<br>

* Exemplo: ``if-else``
  
  ````kotlin
  val nome: String? = "Gabriel"

  val comprimento: Int = if (nome != null) nome.length else 0
  ````
  
* Exemplo: ``?:``
  
  ````kotlin
  val nome: String? = "Gabriel"

  val comprimento: Int = nome?.length ?: 0
  ````
