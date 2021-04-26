# String

## Propriedades

### ```isEmpty()```

* Se não conter nenhum caractere na String, o método retorna ```true```, caso contrário, ```false```.
* Exemplo
  
  ```kotlin
  var language = "Kotlin"
  println(language.isEmpty()) // false

  language = ""
  println(language.isEmpty()) // true
  ```
  

### ```length```

* Quantidade de caracteres presente na String.
* Exemplo
  
  ```kotlin
  println("Hello World".length) // 11
  ```
  
### ```decapitalize()```

* Retorna uma cópia da String com a primeira letra em caixa baixa.
* Exemplo
  
  ```kotlin
  println("Hello World".decapitalize()) // hello World
  ```

### ```toLowerCase()```

* Retorna uma cópia da String com todas as letras em caixa baixa.
* Exemplo
  
  ```kotlin
  println("HeLlo WoRld".toLowerCase()) // hello world
  ```
