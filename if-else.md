# If-Else

## O que é?

* Estrutura de controle de fluxo
* Pode ser passada como uma expressão
* **OBS**: não existe operador ternário, uma vez que if-else possui o mesmo comportamento que ele.

## Como usar?

````kotlin
if (condição) {
  // será executado com a condição for satisfeita (true)
} else {
  // será executado com a condição não for satisfeita (false)
}
```` 

## Exemplos

### Expressão if

````kotlin
val idade = 20

if (idade >= 18) {
  println("Maior de idade")
}
````

### Expressão if em uma linha

````kotlin
val idade = 20

if (idade >= 18) println("Maior de idade")
````


### Expressão if-else

````kotlin
val idade = 16

if (idade >= 18) {
  println("Maior de idade")
} else {
  println("Menor de idade")
}
````

### Expressão if-else em uma linha

````kotlin
val idade = 16

if (idade >= 18) println("Maior de idade") else println("Menor de idade")
````

### Encadeamento de if-else

````kotlin
val calories = 2000

if (calories >= 2000) {
    println("Você atingiu seu limite diário de calorias.")
} else if (calories > 1500) {
    println("Você está perto de atingir seu limite diário de calorias.")
} else {
    println("Você está longe de atingir seu limite diário de calorias.")
}
````
