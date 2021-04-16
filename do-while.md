# Do-While

## O que é?

* Laço de repetição
* É idêntico ao **do-while** do Java


## Como usar?

* Palavras chave: **do** e **while**
* O laço ficará repetindo enquanto a condição (entre parênteses) for verdade
* **OBS**: o código que estiver dentro do bloco **do** será executado pelo menos 1 vez

<br>

* Exemplo
  ```kotlin
  do {
    // TODO
  } while (condição)
  ```
  
## Exemplos em projetos

### kotlin-courses

* **Exemplo**
  ```kotlin
  var temperatura: Int
  var somatoria = 0
  var quantidade = 0

  do {
      println("Digite uma temperatura ou 999 para sair:")
      temperatura = readLine()!!.toInt()

      if (temperatura != 999) {
          somatoria += temperatura
          quantidade++
      }
  } while (temperatura != 999)

  println("A média das temperaturas é = ${somatoria / quantidade}")
  ```
* **Código fonte**: clique [aqui](https://github.com/ImGabreuw/kotlin-courses/blob/master/douglas-motta/do-while/src/main/kotlin/Main.kt)
