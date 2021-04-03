# O que é [Kotlin](https://kotlinlang.org/)?

* Linguagem de programação moderna destinada a plataforma Java (JVM)
* Concisa, segura, pragmática e focada na interoperabilidade com código Java
* è utilizada em quase todos os lugares de Java é utilizado hoje
* Funciona muito bem com todoas as bibliotecas Javas existentes
* Roda com o mesmo nível de performance que java

# Onde é utilizada?

* Backends de aplicações web
* Aplicações mobile que rodam em dispositivos Android
* Aplicações mobile que rodam em dispositivos IOS com utilização do Intel Multi-OS Engine
* Para construir aplicações desktop com a utilização do TornadoFX e JavaFX

# Características

## Estaticamente tipada e faz inferência de tipos

* Tipo de cada expressão é conhecido em tempo de compilação (assim como no Java)
* Não é obrigatório especificar o tipo da variável (diferente do Java)
* O tipo da variável é determinado pelo contexto, ou seja, pelo valor (conteúdo)

* Exemplo
  ```kotlin
  val x = 1 // O compilador infere que essa variável é do tipo Int
  ```
  
## Paradigma Orientado a Objetos

* É muito familiar para os desenvolvedores java (Herança, Classes, Métodos, Polimorfismo, Padrões de Projeto, etc)

## Paradigma Funcional

* Paradigma **Funcional** pode ser novo para muitas pessoas, pois há um domínio específico onde linguagens puramente funcionais são utilizadas
* Conceitos-chave
  * **Funções de 1º classe** - Atribuição de funções nas variáveis, com isso é possível passá-las como parâmetro ou retorno
  * **Imutabilidade** - Objetos que uma vez criada, não pode ser alterada depois
  * **Sem efeitos colaterias** - Retornam o mesmo resultado dada a mesmo esntrada
  
## Gratuita e Open-source

* Kotlin, Compilador e todas as ferramentas relacionadas as essa linguagem
* Disponível sob a licença Apache 2
* [Repositório do Kotlin](https://github.com/JetBrains/kotlin)
  
# Vantagens

## Tipagem Estática

* **Performance** - Não exite a necessidade de escobrir em tempo de execução que método necessita ser chamado
* **Confiabilidade/Manutenibilidade** - Poucas chances para crashes em tempo de execução
* **Suporte de ferramentas** - Possibilitam refatorações confiáveis, auto-complete e outras funcionalidades

## Paradigma Funcional

* **Concisão** - Mais elegante e sucinto comparado ao estilo imperativo (Funções de primeira clase)
* **Multithreading safe** - Funções puras e estruturas de dados imutáveis eliminam possíveis alterações indevidas durante o processo
* **Testar e mais fácil** - funções sem efeitos colaterais facilitam o isolamento do erro, sem requerer uma grande quantidade de código de setup 
