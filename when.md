# when

## O que é?

* Substituto do **switch** do Java
* É uma expressão (**corpo de expressão**) que retorna um valor, assim como o **if**
* Não precisa escrever a **break** no final de cada branch, como no Java
* Podemos combinar múltiplos valores (**separando com vírgula**) na mesma branch.

## when sem argumentos

### O que é?

* Não recebe argumentos

### Como usar?

* Palavra chave: **when**

<br>

* Exemplo
  ```kotlin
  fun fizzBuzz(numero: Int) = when {
      numero % 15 == 0 -> "FizzBuzz "
      numero % 3 == 0 -> "Fizz "
      numero % 5 == 0 -> "Buzz "
      else -> "$numero"
  }
  ```
  
## Exemplos em projetos

### kotlin-courses

* **Exemplo**
  ```kotlin
  fun fizzBuzz(numero: Int) = when {
      numero % 15 == 0 -> "FizzBuzz "
      numero % 3 == 0 -> "Fizz "
      numero % 5 == 0 -> "Buzz "
      else -> "$numero"
  }

  fun main() {
      for (numero in 1..100) {
          println(fizzBuzz(numero))
      }
  }
  ```
* **Código fonte**: clique [aqui](https://github.com/ImGabreuw/kotlin-courses/blob/master/douglas-motta/for/src/main/kotlin/Main.kt)
