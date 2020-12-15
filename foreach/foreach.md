#Estrutura de repetição forEach
>A estrutura de repetição forEach() funciona de forma similar ao forin e é utilizada p/ aplicação em Array()

## Como utilizar o forEach()na prática?

```js
var listaFuncionarios = Array('Jonathan', 'Hélio', 'Mauricio', 'Fernando', 'Mônica', 'Meiry')

var f = function(valor, indice, array) {
    console.log('índice ' + indice + ' | valor ' + valor)
}

listaFuncionarios.forEach(f)
```

No código acima, o forEach chama a função f que por sua vez exibe os dados do Array de forma: indice x valor x.