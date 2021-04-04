# Assessores customizados

## O que são?

* São os métodos **getters** e **setters** com alguma implementação neles.

## Como criar?

* 1º Forma
  ```kotlin
  class Retangulo(
    val altura: Int,
    val largula: Int
  ) {
    val isQuadrado: Boolean
        get() {
            return altura == largula
        }
  }
  ```

* 2º Forma
  ```kotlin
  class Retangulo(
    val altura: Int,
    val largula: Int
  ) {
    val isQuadrado: Boolean
        get() = altura == largula
  }
  ```
  

* 3º Forma
  ```kotlin
  class Retangulo(
    val altura: Int,
    val largula: Int
  ) {
    fun isQuadrado(): Boolean {
         return altura == largula
    }
  }
  ```


* 4º Forma
  ```kotlin
  class Retangulo(
    val altura: Int,
    val largula: Int
  ) {
    fun isQuadrado(): Boolean = altura == largula
  }
  ```

* **isQuadrado** não necessita de uma campo para guardar o valor
* * Somente um **getter** customizado com a implementação fornecida
* O valor é computado toda vez que a propriedade é acessada
