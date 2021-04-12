# While

## O que é?

* Laço de repetição
* É idêntico ao **while** do Java


## Como usar?

* Palavra chave: **while**
* O laço ficará repetindo enquanto a condição (entre parênteses) for verdade

<br>

* Exemplo
  ```kotlin
  while (condição) {
    // TODO
  }
  ```
  
## Exemplos em projetos

### kotlin-courses

* **Código fonte**: clique [aqui](https://github.com/ImGabreuw/kotlin-courses/blob/master/douglas-motta/while/src/main/kotlin/Main.kt)
* **Exemplo**
  ```kotlin
  var temperatura = 0
  var somatoria = 0
  var quantidade = 0

  while (temperatura != 999) {
      println("Digite uma temperatura ou 999 para sair:")
      temperatura = readLine()!!.toInt() //"abc" Erro (NumberFormatException)

      if (temperatura != 999) {
          somatoria += temperatura // somatoria = somatoria + temperatura
          quantidade++ // quantidade = quantidade + 1
      }
  }
  ```
