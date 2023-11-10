---
title: DOM
tags:
  - javascript
---
# Document of Object Model - DOM

É uma interface que representa documentos HTML e XML através de objetos. Com ela é possível manipular a estrutura, estilo e conteúdo destes documentos.

![DOM](https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Fmedia.geeksforgeeks.org%2Fwp-content%2Fuploads%2F20210908120846%2FDOM.png&f=1&nofb=1&ipt=2564255af741a38053c07656c04c89b4ca739c45c71a00d9a652249358847280&ipo=images")


```js
console.log(window);
// windom é o objeto global do browser
// possui diferentes métodos e propriedades

window.innerHeight // retorna a altura do browser
```

## Alguns exemplos de como manipular o DOM

### forEach

O forEach nos auxilia ao querermos selecionar uma lista de itens do DOM.

```js
const imgs = document.querySelectorAll('img')

imgs.forEach(function(item) {
	console.log(item);
})
```

### forEach e Array

forEach é um método de Array, alguns objetos array-like possuem esse método. Caso não possua, o ideal é transformá-los em uma array.

```js
const titles = document.getElementsByClassName('title');
const titlesArray = Array.from(titles);

titlesArray.forEarch(function(item) {
	console.log(item);
})
```

### Arrow Function

Sintaxe curta em relação a <b>function expression</b>. Basta remover a palavra chave function e adicionar a fat arrow <b>=></b> após os arumentos.

```js
const imgs = document.querySelectorAll('img');

imgs.forEach((item) => {
	console.log(item)
})
```

### Eventos

Adiciona uma função ao elemento, esta chamada de <b>callback</b> que será ativada assim que certo <b>evento</b> ocorrer neste elemento

```js
const img = document.querySelector('img');

// element.addEventListener(event, callback, options)
img.addEventListener('click', function() {
console.log("Click!")
})
```

### Callback

Podemos separar a função de callback do addEventListener, ou seja, declarar uma função ao invés de passar diretamente uma função anônima.

```js
const img = document.querySelector('img');

function callback() {
	console.log('Clicou')
}

// usando a função declarada
img.addEventListener('click', callback)
```


