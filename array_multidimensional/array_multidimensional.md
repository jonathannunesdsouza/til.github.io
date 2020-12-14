# Array multidimensional no JavaScript
>O que são e como aplicar Arrays multidimensionais no JavaScript

## O que é um Array multidimensional?

Um ***Array() multidimensional*** nada mais é que um Array() com outros Array() encadeados a ele, por exemplo, uma lista, com sub-listas.

- dados pessoais
    - nome
    - cpf
    - rg

## Como funciona um Array multidimensional na prática?

Vamos supor que precisamos criar uma lista de alimentos e dentro dessa lista, temos duas outras listas, uma lista de alimentos salgados e outra lista de alimentos doces, então, representando isso na forma de uma Array multidimensional:

```js
lista_alimentos = Array()

alimentos_salgados = Array('carne', 'frango','feijão')
alimentos_doces = Array('pão doce', 'biscoito', 'bolo')
```
Desta forma, criamos um Array() lista de alimentos, e dentro dele, inserimos dois outros Arrays p/ alimentos salgados e alimentos doces.