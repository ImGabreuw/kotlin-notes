# Smart Cast

## O que é?

* O compilador faz o cast automático de uma variável após a verificação de um determinado tipo.Sendo assim, não é preciso fazer o cast explícito, como no Java.

## Como fazer a verificação do tipo de uma variável?

* Palavra chave: **is**
* **OBS**: **is** é equivalente ao **instanceof** do Java

<br>

* Exemplo 
  ```kotlin
  if (valor is Int) {
    // TODO
  }
  ```
  
## Como fazer uma cast explícito?

* Palavra chave: **as**

<br>

* Exemplo
  ```kotlin
  if (valor is Int) {
    val numeroInteiro = valor as Int // Desnecessário
  }
  ```
  
## Exemplos em projetos

* [kotlin-courses](https://github.com/ImGabreuw/kotlin-courses/blob/master/douglas-motta/smart-cast/src/main/kotlin/Main.kt)
