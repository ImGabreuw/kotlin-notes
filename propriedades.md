# Propriedades

## O que são propriedades em Java?

* A ideia de uma classe é encapsular dados e códigos que trabalham sobre esses dados dentro de uma única entidade
* O dado é armazenado em campos, que são usualmentes privados
* Se você necessita deixar o cliente da classe acessar esse dado, você fornece métodos assessores: **getters** e **setters**
* A combinação de campo e seu assessor é frequentemente referenciado como uma propriedade

## O que são propriedades em Kotlin

* Funcionalidade de linguagem de primeira-classe
* Inteiramente substitui campos e métodos assessores

<br>

* Exemplo
  ```kotlin
  class Pessoa(
    val nome: String,
    val idade: Int,
    var isCasado: Boolean
  )
  ```
