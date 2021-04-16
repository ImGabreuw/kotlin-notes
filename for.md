# For

## O que é?

* Um laço de repetição
* Não exite o laço **for** convensional do Java (```for(i = 0; i < 10; i++){}```)
* Esse laço usa o conceito de **ranges**, ou seja, um intervalo entre 2 valores

## Como usar?

* Operador para representação de um **range**: ```..```
* Palavra chave: ```for``` e ```in```

* **OBS**: **ranges** são fechados ou inclusivos, ou seja, o segundo valor faz parte do intervalo (```1..10```)

<br>

* Exemplo
  ```kotlin
  for (numero in 1..100) {
      println(fizzBuzz(numero))
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
