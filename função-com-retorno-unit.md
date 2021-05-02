# Função com retorno com ``Unit``

## O que é?

* Se uma função não retornar nenhum valor útil, seu tipo de retorno será ``Unit``
* ``Unit`` é igual ao ``Void`` no Java
* **Documentação**: [clique aqui](https://kotlinlang.org/docs/functions.html#unit-returning-functions)

## Como usar?

### Exemplo: ``Unit`` implícito
````kotlin
fun olaMundo() {
    println("Olá mundo!")
}
````

### Exemplo: ``Unit`` explícito
````kotlin
fun olaMundo(): Unit {
    println("Olá mundo!")
    // 'return Unit' ou 'return' (opcional)
}
````
