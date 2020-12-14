# Estrutura de repetição for in
>Como utilizar a estrutura de repetição for in.

Vamos supor que temos um Array() lista de convidados e queremos saber os nome de cada convidado, percorrendo os índices desse Array, p/ isso, podemos utilizar o for in:

```js 
listaConvidados = Array('João', 'Pedro', 'Matheus')

for (var x in listaConvidados) {
    console.log('índice ' + x + ' valor ' + listaConvidados[x])
}
```