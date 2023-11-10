---
title: JavaScript
tags:
  - javascript
---
# Sobre

É uma linguagem interpretada pelo navegador.
## O básico

As variáveis são basicamente responsáveis pelo armazenamento dos dados na memória do computador.

Tipos ou variáveis:

- var (um tipo de variável simples)
- let (seu valor pode ser alterado)
- const (seu valor não pode ser alterado)

```js
var varVariable = "indeed, a variable"
let letVariable = "indeed, a variable"
const letVariable = "indeed, a variable"
```

Além disso, é possível criar uma variável sem valor.

exemplo: <b>const userId</b>

Será <b>indefinido</b>.

### Algumas regras

- As variáveis podem iniciar com: $, _ ou letras.
- Maiúsculas e minúsculas
- variavel é diferente de variavel
- Não utilize palavras reservadas
- CamelCase

```js
// Invalid

let #name
let function
let 1haveCar
```

```js
// Valid

let $select
let _name
let haveCar
```

### Tipos de dados

Existem 7 tipos de dados. Todos eles são primitivos, exceto objetos, e os primitivos são dados imutáveis.

- String -> letName = 'Mari';
- Número -> let yearsOld = 20;
- Boolean -> let hasCollege = true;
- Indefinido -> let time;
- Nulo -> let favoriteGame= null;
- Símbolo -> let symbol = Symbol()
- Objeto -> let techSkills = {}

### Template String

É quando usamos <b>${your_variable}</b> para chamar uma variável.

```js
let foodOne = "Pizza"
let FoodTwo = "French fries"
let phrase = `I really like ${foodOne} and ${foodTwo} `
```


### Boolean

Boolean é uma comparação condicional, <b>true or false</b>. 

```js
const usesIsModerator = true;

if(userIsModerator) {
	console.log('Can access.')
} else {
console..log ('Cant access.')
}

// Irá retornar quando for true
```

#### Else If

Se o if não for verdadeiro, ele testa o else if.

```js

// Plataforma de moderação

let customUser = false;
let moderatorUser = true;

if(customUser) {
	console.log('Cant access')
} else if (moderatorUser) {
	console.log('Cant access')
} else {
	console.log('Need to be a moderator to access the platform')
}
```


#### Truthy e Falsy

Existem valores que retornam true e outros que retornam false quando verificados em uma expressão booleana.

```js
// Falsy
if(false)
if(0) // ou - 0
if(NaN)
if(null)
if(undefined)
if('') // ou "" ou ``
```

#### Operadores de comparação

Vão sempre retornar um valor booleano.

```js
10 > 5 // true
5 > 10 // false
20 < 10 // false
10 <= 10 // true
10 >= 11 // false
```

```js
10 == '10' // true
10 == 10 // true
10 === '10' // false
10 === 10 // true
10 != 15 // true
10 != '10' // false
10 !== '10' //true
```

#### Operadores Lógicos &&

&& Compara se uma expressão e a outra é verdadeira.

```js
true && true // true
true && false // false
false && true // false
'Cat' && 'Dog' // 'Dog'
(5-5) && (5 + 5) // 0
'Cat' && false // false
(5 >= 5) && (3 < 6) // true
```

#### Operadores Lógicos ||

|| Compara se uma expressão <b>ou</b> outra é verdadeira.

```js
true || true // true
true || false // true
false || true // true
'Cat' || 'Dog' // 'Cat'
(5-5) || (5+5) // 10
'Gato' || false; // Cat
(5 >= 5) || (3 < 6) // true

// Retorna o primeiro valor true que encontrar
```



### Switch

Com o <b>switch</b> você pode verificar se uma variável é igual à diferentes valores utilizando o <b>case</b>.
Caso ela seja igual, você pode fazer atribuir uma funcionalidade e utilizar a plavra chave <b>break</b> para cancelar a continuação. O valor de default ocorrerá caso nehuma das anteriores seja verdadeira.

```js
let favoriteColor = 'Green';

switch (favoriteColor) {
	case 'Blue':
		console.log('Look to the sky')
		break
	case 'Yellow':
		console.log('Look to the sun')
		break
	case 'Green':
		console.log('Look the florest')
		break
	default:
		console.log('Close the eyes.')
}
```

### Function

Function ou Função é um bloco de código que pode ser executado e reutilizado. Valores pode ser passados por uma função e a mesma retorna outro valor.

```js
function areaSquare(side) {
return side * side
}

areaSquare(4) // 16
areaSquare(5) // 25
areaSquare(2) // 4

// Function declaration
```



