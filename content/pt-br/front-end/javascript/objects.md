---
title: Objetos
tags:
  - javascript
  - objetos
---
# Funções construtoras 

## Objetos

Um objeto é uma variável que contém atributos, propriedades e métodos.

```js
const course = {
	name: 'Node.js',
	teacher: 'Name',
	price: 0,
	certificate: true,
	hours: 130
}
```

### Constructor Functions

Funções Construtoras são responsáveis por construir novos objetos sempre que chamamos a mesma.

```js
function Car() {
	this.brand = 'Brand'
	this.price = 0
}

// objeto do tipo Car baseado na função construtora

const honda = new Car()
honda.brand = 'Honda'
honda.price = 4000

const fiat = new Car();
fiat.brand = 'Fiat'
fiat.price = 3000
```


### new (Keyword)

A palavra chave <b>new</b> é responsável por criar um novo objeto baseado na função que passarmos a frente dela.

```js
	const honda = new Car()

	// 1 - Cria um novo objeto
	honda = {}
	// 2 Define o protótipo
	honda.prototype = Car.prototype
	// 3 - Aponta a variável this para o objeto
	this = honda
	// 4 - Executa a função, substituindo this pelo objeto
	honda.brand = 'Honda'
	
```
