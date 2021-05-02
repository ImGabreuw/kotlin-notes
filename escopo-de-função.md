# Escopo de função

## O que é?

* Função local são funções dentro de outra função
* **Documentação**: [clique aqui](https://kotlinlang.org/docs/functions.html#local-functions)

## Como usar?

### Exemplo: Função local

Na função ``main`` a função ``tchau`` não é visível pois o escopo dela é apenas dentro da função ``olaETchau`` e depois de sua declaração. Veja o exemplo abaixo:

````kotlin
fun main() {
  olaETchau()
  tchau() // Erro de compilação
}

fun olaETchau() {
  println("Olá")

  tchau() // Erro de compilação

  fun tchau() {
      println("Tchau")
  }

  tchau()
}
````

## OBS

* **CUIDADO** com o uso excessivo de funções locais, pois pode prejudicar o entendimento do código
