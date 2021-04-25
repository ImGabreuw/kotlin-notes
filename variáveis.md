# Variáveis

## O que são?

* Representa um valor ou expressão na memória
* É declarada com a palavra-chave **var** e **val** seguido do nome
* O tipo da variável pode ser especificado ou não depois do nome

## Como usar?

```kotlin
val nome = "Gabriel" // Inferência de tipo
val nome: String = "Gabriel" // declaração do tipo

var nome: String
nome = "Gabriel"
```

* 1º - declarar se é **val** ou **var**
* 2º - definir um nome
* 3º - atribuir um valor ou apenas declarar a assinatura da variável

* **BOAS PRÁTICAS** - é preferível deixar o tipo da variável implícito.

## Qual a diferença entre **val**  e **var**

* val - representa uma referência imutável, ou seja, seu estado uma vez declarada não pode ser alterada. (**OBS:** equivalente ao **final** do Java)
* var - representa uma referência mutável, ou seja, o valor da variável pode ser alterado mesmo depois de ser declarada
