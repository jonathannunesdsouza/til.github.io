# BOM utilizando o objeto Timing
>O objeto timing possui diversas métodos, alguns deles são setInterval() e setTimeout()

## Para que serve o método setInterval()

O método ***setInterval()*** serve para executar uma determinada ação em um intervalo de tempo, por exemplo, a cada 5 segundos regarregar o browser.

## Sintaxe do setInterval()

```js
setInterval(function(){
    //ação a ser executada
}, /*intervalo de tempo em milissegundos*/)
```
Tendo isso em vista, a codificação de um script que recarrega a página a cada 5 segundos seria da seguinte maneira:

```js
var contador = 5
var intervalo = setInterval(function() {
    
    contador--

    if (contador === 0) {
        clearInterval(intervalo)
    }

}, 1000 )
```

## Para que serve o método setTimeout()

O método ***setTimeout()*** serve para executar uma ação a apenas uma vez, após o tempo determinado no script, por exemplo, exibir uma valor na página após 5 segundos que ela foi carregada.

## Sintaxe do setTimeout()

```js
setInterval(function() {
    /*ação a ser executada após o tempo determinado*/
}, /*tempo determinado para ação ser executada em milisegundos*/ )
```

Tendo isso em vista, a codificação de um script que exibe um valor na página após 5 segundos seria da seguinte maneira:

```js
setTimeout(function() {
    document.write('Valor exibido após 5 segundos.')
}, 5000)
```