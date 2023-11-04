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
