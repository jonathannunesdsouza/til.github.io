# Estrutura de repetição do while
>A diferença entre o while e o do while é que o do while executa um bloco de código antes de ser feita uma verificação de true or false.

## Qual a diferença entre o while e o do while?

Como podemos ver no código abaixo, na estrutura de repetição while, a sintaxe efetua um teste lógico e a partir do resultado deste, executa um bloco de código.

```js
var x = 0

while (x <= 10) {
    document.write(x + '</br>')
    x++
}
```
Quando se trata da estrutura de repetição *do while*, o assunto é diferente, ela executa primeiro um bloco de código e somente depois faz um teste lógico:

```js
var x = 11
do {
    document.write(x)
} 
while (x < = 10>)
}
```
Neste caso, podemos notar que mesmo o teste lógico resultando em *false*, o JavaScript retorna o valor de x sem que a aplicação dê erro, isso porque, este é o modo de funciona o do while.