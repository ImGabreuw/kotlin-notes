# Triple quotes

## O que é?

* String com quebra de linha sem precisar usar o caracter especial ````\n```` 

## Como usar?

* ````trimIndent()```` 

  É o método padrão no uso de triple quotes

  ````kotlin
  val mensagem = """
      Olá
      Mundo
  """.trimIndent()
  ```` 
  

* ````replaceIndent()```` 

  É idêntico ao método ````trimIndent()````

  ````kotlin
  val mensagem = """
      Olá
      Mundo
  """.replaceIndent()
  ```` 
  
* ````trimMargin()```` 
  
  Esse método substitui a indentação pela String passada como argumento

  ````kotlin
  val mensagem = """
      Olá
      Mundo
  """.replaceIndent(">")
  ```` 
  
* ````trimMargin()```` 

  Esse método faz a quebra de linha, por padrão, a partir de ````|```` (**pipe**)
  
  ````kotlin
  val mensagem = """
      Olá
      Mundo
  """.trimMargin()
  ```` 
  
* ````trimMargin()```` 

  Esse método faz a quebra de linha a partir da String passada como aargumento
  
  ````kotlin
  val mensagem = """
      >Olá
      >Mundo
  """.trimMargin(">)
  ```` 
