# Desafio da semana #2

Nesse exercício, você está livre para escolher os nomes para suas variáveis e funções! :smile:

```js
// Crie uma função que receba dois argumentos e retorne a soma dos mesmos.
 function soma (x,y) {
  return x + y
 }

// Declare uma variável que receba a invocação da função criada acima, passando dois números quaisquer por argumento, e somando `5` ao resultado retornado da função.
var sum = soma(3,4) + 5


// Qual o valor atualizado dessa variável?
12

// Declare uma nova variável, sem valor.
var noValue; 

/*
Crie uma função que adicione um valor à variável criada acima, e retorne a string:
    O valor da variável agora é VALOR.
Onde VALOR é o novo valor da variável.
*/
function showValue(){
  noValue = 10
  return 'O valor da variável agora é ' + noValue
 }

// Invoque a função criada acima.
showValue(noValue,10)

// Qual o retorno da função? (Use comentários de bloco).
/*o valor da variavel agora eh 10 */

/*
Crie uma função com as seguintes características:
1. A função deve receber 3 argumentos;
2. Se qualquer um dos três argumentos não estiverem preenchidos, a função deve retornar a string:
    Preencha todos os valores corretamente!
3. O retorno da função deve ser a multiplicação dos 3 argumentos, somando `2` ao resultado da multiplicação.
*/
function checkValues (a,b,c) {
    if(a === undefined || b === undefined || c === undefined){
        return 'algum parametro nao foi preenchido';
    }
    return (a * b * c) + 2;
}

// Invoque a função criada acima, passando só dois números como argumento.
checkValues(10,20)

// Qual o resultado da invocação acima? (Use comentários para mostrar o valor retornado).
algum parametro nao foi preenchido

// Agora invoque novamente a função criada acima, mas passando todos os três argumentos necessários.
checkValues(10,20,20)

// Qual o resultado da invocação acima? (Use comentários para mostrar o valor retornado).
// 52

/*
Crie uma função com as seguintes características:
function threeArgs(x,y,z) {
  if(x !== undefined && y === undefined && z === undefined) {
    return x;
  } else if(x !== undefined && y !== undefined && z === undefined) {
    return x + y;
  } else if(x !== undefined && y !== undefined && z !== undefined) {
    return (x+y) / z;
  } else if(x === undefined && y === undefined && z === undefined) {
    return false
  } else {
    return null
  }
}

// Invoque a função acima utilizando todas as possibilidades (com nenhum argumento, com um, com dois e com três.) Coloque um comentário de linha ao lado da função com o resultado de cada invocação.
// false
// 1
// 3
//

```
