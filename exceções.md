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
  throw IllegalArgumentException()
  ```
  
## Como tratar uma exceção?

* Palavra cahve: ```try``` ```catch``` ```finally```

<br>

* Exemplo com bloco TRY-CATCH
  ```kotlin
  try {
    // Código
  } catch (e: Exception) {
    // Código
  }
  ```
  
* Exemplo com bloco TRY-CATCH-FINALLY
  ```kotlin
  try {
    // Código
  } catch (e: Exception) {
    // Código
  } finally {
    // Código
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

---

* **Exemplo**
  ```kotlin
  fun lerIdade(): Int? {
    val reader = BufferedReader(
        FileReader(
            File("src/main/resources/idades.txt")
        )
    )

    return try {
        Integer.parseInt(reader.readLine())
    } catch (e: NumberFormatException) {
        null
    } finally {
        reader.close()
    }
  }
  ```
* **Código fonte**: clique [aqui](https://github.com/ImGabreuw/kotlin-courses/blob/master/douglas-motta/tratar-excecoes/src/main/kotlin/Main.kt)
