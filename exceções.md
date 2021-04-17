# Exceções

## O que é?

* Similar com o Java
* É uma expressão, ou seja, é possível ser um retorno de uma função
* É lançado quando um função não é completada de forma correta
* É possível tratá-la ou apenas propagá-la

## Como lançar uma exceção?

* Palavra chave: ```throw```

<br>

* Exemplo
  ```kotlin
  fun suaFuncao(valor) = 
    if (condicao) {
      // Código
    } else {
      throw IllegalArgumentException()
    }
  ```

## Exemplos em projetos

### kotlin-courses

* **Exemplo**
  ```kotlin
  fun porcentagem(numero: Int): String {
      return if (numero in 1..100) {
          "$numero%"
      } else {
          throw IllegalArgumentException("$numero deve estar entre 1 e 100")
      }
  }
  ```
* **Código fonte**: clique [aqui](https://github.com/ImGabreuw/kotlin-courses/blob/master/douglas-motta/lancar-excecoes/src/main/kotlin/Main.kt)
