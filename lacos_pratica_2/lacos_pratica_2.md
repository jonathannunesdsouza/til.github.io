# Criando uma tabuada do 1 ao 10 com laços de repetição
>Atividade prática p/ praticar o uso de laços de repetição no JavaScript.

## Criando a tabuada do 1:

P/ criar a tabuada do 1 utiliza-se de um laço de repetição bem simples:

```js
for (x = 1; x <= 10; x++) {
    document.write('1 x ' + x + ' = ' + (1*x) + '</br>')
}
```

## Criando a tabuada do 1 ao 10:

Já p/ criar a tabuada do 1 ao 10, utiliza-se de um modo mais trabalhoso de laços de repetição, pois é preciso encadea-los:

```js
for (y = 1; y <= 10; y++) {

    for (x = 1; x <= 10; x++) {
        document.write('1 x ' + x + ' = ' + (1*x) + '</br>')
    }
  document.write('</br>')
}
