# Igualdade Referencial

## O que é?

* A igualdade referencial é verificada pelo operador ``===``, e sua negação é ``!==``
* **DOCUMENTAÇÂO**: [clique aqui](https://kotlinlang.org/docs/equality.html#structural-equality)

## Como usar?

### Exemplo: ``===`` 
````kotlin
class Pessoa(val nome: String)

fun main() {
  val person1 = Pessoa("Gabriel")
  val person2 = Pessoa("Gabriel")
  
  // person1 e person2 são objetos diferentes, portanto referências distintas
  println(person1 === person2) // false
}
````

### OBS

Para tipos primitivos (números, char, boolean) o operador ``===`` funciona da mesma forma que o ``==``

````kotlin
val a = 12
val b = 12

println(a === b) // true
println(a == b) // true
````

### Exemplo: ``!=`` 
````kotlin
class Pessoa(val nome: String)

fun main() {
  val person1 = Pessoa("Gabriel")
  val person2 = Pessoa("Gabriel")
  
  // person1 e person2 são objetos diferentes, portanto referências distintas
  println(person1 !== person2) // true
}
````
