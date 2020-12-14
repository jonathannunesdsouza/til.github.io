# Percorrendo itens de Array com laço de repetição
>Atividade prática p/ estudar laços de repetição em conjunto com Array()

## Como utilizar um Array em conjunto com laço de repetição while?

Vamos supor temos um Array() com uma lista de frutas, e queremos percorrer os índices desse Array() e exibir os valores contidos (nomes das frutas):

```js
var lista_frutas = Array('Banana', 'Uva', 'Maçã')
```
P/ essa finalidade, podemos utilizar um laço de repetição *while*:

```js
var lista_frutas = Array('Banana', 'Uva', 'Maçã')
var y = 0

while (y < lista_frutas.length) {
    document.write(lista_frutas[y] + '</br>')
    y++
}
```
