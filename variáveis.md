# Variáveis

## O que são?

* Representa um valor ou expressão na memória
* É declarada com a palavra-chave ```var``` e ```val``` seguido do nome
* O compilador pode inferir o tipo da variável com base no valor dela.

## Como usar?

### Inferência de tipo
```kotlin
val nome = "Gabriel" // Tipo = String

val idade = 16 // Tipo = Int
```

### Declaração do tipo

Basta colocar o tipo da variável depois do nome dela. Veja no exemplo a abaixo:

```kotlin
val nome: String = "Gabriel"

val idade: Int = 16
```

* **BOAS PRÁTICAS** - é preferível deixar o tipo da variável implícito.

## Qual a diferença entre **val**  e **var**

* val - representa uma referência imutável, ou seja, seu estado uma vez declarada não pode ser alterada. (**OBS:** equivalente ao **final** do Java)
* var - representa uma referência mutável, ou seja, o valor da variável pode ser alterado mesmo depois de ser declarada
