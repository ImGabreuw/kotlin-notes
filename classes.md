# Classes

## Revisão sobre Orientação a Objetos

* Também conhecido como POO, é um paradginmas de programação baseado no conceito de **"objetos"**
* Objetos podem conter dados (**atributos**) e procedimentos (**métodos**) e são elementos fundamentais na construção da solução
* Objetos são instâncias de classes
* Um objeto é uma abstração de algum fato ou entidade do mundo real

## O que são classes?

* É uma descrição que abstrai um conjunto de objetos com características similares
* Descreve as propriedades/estado (**atributos**) possíveis e as ações/comportamententos (**métodos**) de um conjunto de objetos

## Diferenças entre uma classe Java e Kotlin

* Classe em Java
  ```java
  public class Pessoa {
    private final String nome;
    private final Integer idade;
    
    public Pessoa(String nome, Integer idade) {
      this.nome = nome;
      this.idade = idade;
    }
    
    public String getNome() {
      return nome;      
    }
    
    public Integer getIdade() {
      return idade;      
    }
  }
  ```
  
* Classe em Kotlin
  ```kotlin
  class Pessoa(
    val nome: String
    val idade: Int
  )
  ```
  
* **OBS**
  * objetos valor (value objects) - comtém apenas dados (sem código)
  * em Kotlin, **public** já é por padrão a visibilidade de uma classe

## Como criar uma classe?

```kotlin
class Pessoa(
    val nome: String,
    val idade: Int
)
```

* 1º - Crie uma arquivo Kotlin do tipo **Class**
* 2º - Entre parênteses defina os atributos da classe

## Como instanciar uma classe?

```kotlin
val pessoa = Pessoa("Gabriel", 16)
```

* 1º - Escreva o nome da classe
* 2º - Depois do nome da classe, coloque parênteses
* 3º - Entre parênteses coloque os argumentos da classe

## Como acessar os atributos de uma classe?

```kotlin
println("Pessoa: ${pessoa.nome}")
```

* 1º - Chame a variável que foi atribuída a classe
* 2º - Coloque ponto depois do nome da variável
* 3º - Escolha qual atributo deseja recuperar colocando o nome do atributo depois do "."

## Curiosidade - Como comprovar transformar uma classe Kotlin para Java

* **IMPORTANTE** Utilize o Intellij IDEA

* Siga o seguinte caminho 
  * 1º - Vá para a barra de ferramentas 
  * 2º - Clique em **Tools** 
  * 3º - Clique em **Kotlin**
  * 4º - Clique em **Show Koltin Bytecode**
  * 5º - Clique em **Decompile**
