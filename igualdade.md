# Igualdade Estrutural

## O que é?

* A igualdade estrutural é verificada pelo operador ``==``, e sua negação é ``!=``
* **DOCUMENTAÇÂO**: [clique aqui](https://kotlinlang.org/docs/equality.html#structural-equality)

## Como usar?

### Exemplo: ``==`` 
````kotlin
val nome1 = "Gabriel"
val nome2 = "Gabriel"

println(nome1 == nome2) // true
````

### OBS ``.equals()`` exerce a mesma função que o ``==``. Veja o exemplo abaixo:

````kotlin
val nome1 = "Gabriel"
val nome2 = "Gabriel"

println(nome1.equals(nome2)) // true
````

### Exemplo: ``!=`` 
````kotlin
val nome1 = "Gabriel"
val nome2 = "Kotlin"

println(nome1 != nome2) // true
````
