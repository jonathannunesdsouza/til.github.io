# Pesquisando dados de um Array
>Como pesquisar um dado de um Array().

## Como pesquisar um dado de um Array?

Vamos supor que temos um Array() lista de frutas:

```js
lista_frutas = Array()

lista_frutas[0] = 'banana'
lista_frutas[1] = 'pêra'
lista_frutas[2] = 'uva'
```
E queremos saber pesquisar se o item *"uva"* realmente está contido neste Array(), p/ isso, utilizamos o método **indexOf()** que retorna o índice em que aquela informação procurada está no Array() (implicando que ela exista no Array, caso não exista, o indexOf retornará o valor **-1**).

### Sintaxe do indexOf() c/ Array()

```js
lista_frutas.indexOf('uva')
console.log(lista_frutas.indexOf('uva'))
```