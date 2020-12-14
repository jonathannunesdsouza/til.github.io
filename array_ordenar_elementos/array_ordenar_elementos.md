# Como ordenar elementos em um Array no JavaScript
>Como ordenar elementos no Array() por ordem alfabética e alfanúmerica.

## Ordem alfabética

Vamos supor que temos um Array() lista de frutas:

```js
lista_frutas = Array()

lista_frutas[0] = 'pêra'
lista_frutas[1] = 'uva'
lista_frutas[2] = 'maçã'
```
E queremos exibir os elementos contidos neste Array() por ordem alfabética, p/ isso, utilizamos o **sort()**:

```js
console.log(lista_frutas.sort())
```

## Ordem alfanumérica

Vamos supor que temos um Array() lista de números e queremos exibila em ordem alfanumérica:

```js
lista_numeros = Array()

lista_numeros[0] = 34
lista_numeros[1] = 2
lista_numeros[2] = 55
lista_numeros[3] = 11
```

O recurso utilizado é o mesmo, no entanto, temos que aplicar uma função ao **sort()**, uma função que calcula a ordem de exibição dos valores:

```js 
function ordenaNumeros (a,b) {
    return a - b
}

console.log(lista_numeros.sort(ordenaNumeros))
```