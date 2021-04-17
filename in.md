# Operador in

## O que é?

* Um operador para iterar sobre intervalos
* **OBS**: pode ser usado para verificar se um valor está, ou não, presente em um intervalo

## Como usar?

* Palavra-chave: ```in```

<br>

* Exemplo para verificar se um valor está presente no intervalo (```in```)
  ```kotlin
  fun estaPresente(parametro) = valor in valor1..valor2
  ```
  
* Exemplo para verificar se um valor não está presente no intervalo (```!in```)
  ```kotlin
  fun naoEstaPresente(parametro) = valor !in valor1..valor2
  ```
  
## Exemplos em projetos

### kotlin-courses

* **Exemplo**
  ```kotlin
  fun isLetter(c: Char) = c in 'a'..'z' || c in 'A'..'Z'

  fun isNotDigit(c: Char) = c !in '0'..'9'
  ```
* **Código fonte**: clique [aqui](https://github.com/ImGabreuw/kotlin-courses/blob/master/douglas-motta/operador-in/src/main/kotlin/Main.kt)

