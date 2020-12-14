# Estrutura de repetição do for
>A estrutura de repetição for torna o código menos verboso e de fácil entendimento

## Como utilizar o for na prática?

Vamos supor que queremos fazer uma aplicação que conte uma determinada sequência de números em forma decrescente, um dos métodos p/ fazer isso é utilizando a estrutura de repetição for:

### Sintaxe:

```js
for (variavel; condição; controle) {
    //bloco de código a ser executado após o teste lógico
}
```

Desta forma:

```js
for (var contador = 10; contador >= 0; contador--) {
    //bloco de código a ser executado após o teste lógico
}
```