# String Templates

## O que são?

* Formatação de strings mais fácil
* É possível referenciar variáveis locais em strings literais por colocar o caractere **$** antes do nome da variável
* Isso equivale à concatenação de strings no Java ("Hello " + nome + "!")
* É possível fazer o escape da variável para o compilador não interpretá-la como template - ```\$```
* Pode ser utilizada também como expressão

## Como usar?

* Concatenação de variáveis
  ```kotlin
  val nome = "Gabriel"
  
  println("Hello $nome!")
  ```
  
* Concatenação de expressões

  * **IMPORTANTE:** para que o template funcione a expressão precisa estar entre chaves, ou seja, ```${expressão}```

  <br>

  ```kotlin
  fun main() {
    println("Soma é: ${soma(10, 20)}")
  }
  
  fun soma(a: Int, b: Int) = a + b
  ```
