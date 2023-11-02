---
title: JavaScript
tags:
  - javascript
---
## About

It is a language interpreted by the browser.

## The basics

### Variables

Variables are basically responsible for storing data in the computer's memory.

Types os variables:

- var (a simple variable type)
- let (its value can be changed)
- const (its value cannot be changed)

```js
var varVariable = "indeed, a variable"
let letVariable = "indeed, a variable"
const letVariable = "indeed, a variable"
```

Also, is possible create a variable without value.

example: <b>const userId</b>

It will be <b>undefined</b>.

### Some rules

- The variables can init with: $, _ , or letters.
- Case sensitive
- variavel é diferente de Variavel
- Não utilizar palavras reservadas
- Camel Case

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

### Types of data

There are 7 types of data. All of them are primitive except objects, and primitives are immutable data.

- String -> let name = 'Mari';
- Number -> let yearsOld = 20 ;
- Boolean -> let hasCollege = true;
- Undefined -> let time;
- Null -> let favoriteGame = null;
- Symbol -> let symbol = Symbol()
- Object -> let techSkills = {}

### Template String

Is when we use <b>${your_variable}</b> to call a variable.

```js
let foodOne = "Pizza"
let FoodTwo = "French fries"
let phrase = `I really like ${foodOne} and ${foodTwo} `
```
