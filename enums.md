# Enum

## O que é?

* Um agrupamento de constante
* No Kotlin, a palavra **enum** só é considerado uma keyword somente se vier antes da keyword **class** (**soft-keyword**)
* Não são lista de valores
* Podemos declarar propriedades e métodos

## Diferença entre **enum class** e **enum**

* **enum class**
  ```kotlin
  enum class Cor {
    VERMELHOR,
    LARANJA,
    AMARELO,
    VERDE,
    AZUL
  }
  ```
  
  * **OBS**: por convenção, toda constante de ser escrito em CAPS LOCK

* **enum**
  ```kotlin
  val enum = "abc" // ✔
  ```
  
## Importante

* ";" é obrigatório para separação dos atributos e métodos
* Exemplo
  ```kotlin
  enum class Cor(
    val vermelho: Int,
    val verde: Int,
    val azul: Int
  ) {

      VERMELHO(255, 0, 0),
      LARANJA(255, 165, 0),
      AMARELO(255, 255, 0),
      VERDE(0, 255, 0),
      AZUL(0, 0, 255); // ";" é obrigatório para separação dos atributos e métodos

      fun rgb() = ((vermelho * 256 + verde) * 256 + azul)

  }
  ```
  
## Alguns exemplos em projetos

* [kotlin-courses](https://github.com/ImGabreuw/kotlin-courses/blob/master/douglas-motta/entendendo-enums/src/main/kotlin/Cor.kt)
