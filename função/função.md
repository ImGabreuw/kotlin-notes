# Função

## O que é?

* As funções são declaradas usando a palavra-chave ``fun``
* **Documentação**: [clique aqui](https://kotlinlang.org/docs/functions.html)

## Como usar?

### Criar uma função

Basta usar a palavra-chave ``fun``

````kotlin
fun dobro(x: Int): Int {
    return x * 2
}
````

### Chamar uma função

Mesma forma que no Java, ou seja, basta colocar o nome da função e abre e fecha parênteses.

```kotlin
val resultado = double(2) // 4
```

### Encademamento de funções

Para chamar vários métodos em cadeia, usa-se a notação ``.`` (ponto)

````kotlin
"Olá ".plus("Mundo!").length // 10
````
