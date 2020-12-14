#Array básico no JavaScript
>O que são e como aplicar arrays básicos no JavaScript

## O que é um Array?

Um ***Array()*** nada mais é que um recurso que possibilita armazenar dados relacionados dentro de uma única variável.

## Como funciona um Array na prática?

```js
var frutas1 = 'banana'
var frutas2 = 'uva'
var frutas3 = 'maca' 
```
Como podemos notar, utilizando o método tradicional, precisariamos declarar uma varíavel para armezanar o nome de cada fruta, porém, com um ***Array()*** podemos simplicar esse processo:

```js
var lista_fruta = Array()

lista_fruta[1] = 'banana'
lista_fruta[2] = 'uva'
lista_fruta[3] = 'maca'

```

Com o ***Array()*** podemos agrupar dados relacionados dentro de uma única variável e para acessa-los de acordo com a nossa necessidade, podemos utilizar os índices definidos (por nós ou pelo JavaScript dependendo do modo de uso):

```js
console.log(lista_fruta[1])
```