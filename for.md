# For

## O que é?

* Um laço de repetição
* Não exite o laço **for** convensional do Java (```for(i = 0; i < 10; i++){}```)
* Esse laço usa o conceito de **ranges**, ou seja, um intervalo entre 2 valores

## Como usar?

### Ranges

* Operador para representação de um **range**: ```..```
* Palavra chave: ```for``` e ```in```

* **OBS**: **ranges** são fechados ou inclusivos, ou seja, o segundo valor faz parte do intervalo (```1..10```)

<br>

* Exemplo com números
  ```kotlin
  for (numero in 1..100) {
      // Código
  }
  ```
  
* Exemplo com letras
  ```kotlin
  for (l in 'A'..'F') {
      // Código
  }
  ```
  
### Maps

* Palavra chave: ```for``` e ```in```

* Exemplo
  ```kotlin
  for ((chave, valor) in MeuMap) {
      // Código
  }
  ```
  
## Exemplos em projetos

### kotlin-courses

* **Exemplo de ranges de números**
  ```kotlin
  for (numero in 1..100) {
      println(fizzBuzz(numero))
  }
  ```
* **Código fonte**: clique [aqui](https://github.com/ImGabreuw/kotlin-courses/blob/master/douglas-motta/for/src/main/kotlin/Main.kt)

---

* **Exemplo de range de letras**
  ```kotlin
  for (c in 'A'..'F') {
      val binary = Integer.toBinaryString(c.toInt())
      binaryRepresentation[c] = binary
  }
  ```
* **Código fonte**: clique [aqui](https://github.com/ImGabreuw/kotlin-courses/blob/master/douglas-motta/iteracao-em-maps/src/main/kotlin/Main.kt)

---

* **Exemplo de iteração em Maps**
  ```kotlin
  for ((letra, binary) in binaryRepresentation) {
      println("$letra - $binary")
  }
  ```
* **Código fonte**: clique [aqui](https://github.com/ImGabreuw/kotlin-courses/blob/master/douglas-motta/iteracao-em-maps/src/main/kotlin/Main.kt)
