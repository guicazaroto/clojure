# Clojure

## Introdução
Clojure é uma linguagem orientado ao paradigma funcional, baseada na linguagem Lisp. Portanto, possui enfâse em conceitos como imutabilidade e sintaxe declarativa.

### Hello World
Repare que o parâmetro é separado da função por espaço

```
(println "Hello World")
```

### Definindo símbolos
No exemplo abaixo definimos um símbolo que faz referência a uma matriz

````
(def estoque ["cadeira", "mesa", "televisao"])
````

### Realizando operações
Na operação abaixo definimos um símbolo "total" com o valor de 20 e em seguida definimos outro símbolo "resultado "que é igual a soma de total com 30
```
(def total 20)
(def resultado (+ total 30))
```

### Definindo Funções

```
(defn
  "Retorna o 90% do valor total"
  valor-descontado
  [valor]
  (* valor 0.9)
)
```
