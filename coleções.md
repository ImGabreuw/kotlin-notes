# Coleções

## O que são?

* Kotlin não possui seu próprio conjunto de coleções (List, Map, Set, etc)
* Kotlin usa as classes de coleções do Java
* Kotlin possuí algumas algumas funcionalidades extras nessa coleções

## ArrayList

### Como usar

* 1º Forma - Instanciando a Classe ```ArrayList```
  ```kotlin
  val exemploArrayList = ArrayList<String>()
  exemploArrayList.add(elemento1)
  exemploArrayList.add(elemento2)
  ```

* 2º Forma - Usando a função ```arrayListOf```
  ```kotlin
  val exemploArrayList = arrayListOf(elemento1, elemento2)
  ```
  
### Funcionalidades extras do Kotlin

* ```last``` 
  
  * Pegar o último elemento do ArrayList
  
  * Exemplo
    ```kotlin
    exemploArrayList.last()
    ```
    
## Set

### Como usar

* 1º Forma - Instanciando a Classe ```Set```
  ```kotlin
  val exemploSet = HashSet<Int>()
  exemploSet.add(elemento1)
  exemploSet.add(elemento2)
  ```

* 2º Forma - Usando a função ```setOf```
  ```kotlin
  val exemploSet = setOf(elemento1, elemento2)
  ```
  
### Funcionalidades extras do Kotlin

* ```max``` 
  
  * Pegar o maior número do Set
  
  * Exemplo
    ```kotlin
    exemploSet.max()
    ```
    
## Exemplos em projetos

### kotlin-courses

* **Exemplo**
  ```kotlin
  val frutas1 = ArrayList<String>()
  frutas1.add("Maça")
  frutas1.add("Banana")
  frutas1.add("Morango")
  println(frutas1)

  val frutas2 = arrayListOf("Maça", "Banana", "Morango")
  println(frutas2)
  ```
* **Código fonte**: clique [aqui](https://github.com/ImGabreuw/kotlin-courses/blob/master/douglas-motta/colecoes/src/main/kotlin/Main.kt)

---

* **Exemplo**
  ```kotlin
  val numeros1 = HashSet<Int>()
  numeros1.add(1)
  numeros1.add(2)
  numeros1.add(3)
  println(frutas1)

  val numeros2 = setOf(1, 2, 3)
  println(frutas1)
  ```
* **Código fonte**: clique [aqui](https://github.com/ImGabreuw/kotlin-courses/blob/master/douglas-motta/colecoes/src/main/kotlin/Main.kt)
