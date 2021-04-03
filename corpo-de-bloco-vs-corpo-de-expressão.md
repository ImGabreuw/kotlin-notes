# Corpo de bloco VS Corpo de expressão

## Corpo de bloco

* É quando uma função é escrita com seu corpo dentro de chaves
* **IMPORTANTE** - tipo de retorno e a declaração do **return** são obrigatórios

## Corpo de expressão

* É quando uma função consiste de apenas uma expressão (valor)
 
* Exemplo
  ```kotlin
  fun max(a: Int, b: Int): Int = if (a > b) a else b
  ```

<br>

* **OBS** - no corpo de expressão é possível omitir o tipo de retorno
  
<br>
  
* Exemplo
  ```kotlin
  fun max(a: Int, b: Int) = if (a > b) a else b
  ```
