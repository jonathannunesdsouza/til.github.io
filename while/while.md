# Estrutura de repetição while
>A estrutura de repetição while repete um bloco de código até uma parada definida por uma condição.

## Como utilizar o while?

Vamos supor que queremos que uma aplicação inicie uma contagem até 10, e chegando neste resultado, a aplicação pare de contar, p/ isso, utilizamos o while:

```js
var contador = 0

while (contador <= 10) {
    document.write(contador + '</br>')
    contador++
}
```