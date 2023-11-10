---
title: Vue.js
---

# Sobre

Vue.js é um framework JavaScript criado por Evan You que visa construir interfaces de página única (SPAs). Ele usa HTML, CSS e JavaScript (ou TypeScript).

Ele faz uma cópia do nosso código e gera uma estrutura para ele manipular e após a manipulação ele usa para fazer o <b>output</b> final e escrever o nosso template no <b>DOM</b>.

Algumas outras informações sobre a estrutura:

- Quadro progressivo
- Simplifica a manipulação do DOM
- Facilita a divisão da interface em componentes, facilitando a manutenção.
- Pode ser utilizado para criar aplicações MPA e SPA


## Instância

Quando se cria uma aplicação Vue.js, você instancia um objeto Vue que representa e controla a interface do usuário e os dados associados a ela.
Para criar uma instância Vue, é necessário passar um objeto de opções, que pode incluir:

- El (element): Onde a instância Vue será montada no DOM.
- Data(dados): Os dados que a instância Vue usará para renderizar o template. Esses dados são reativos, o que significa que qualquer mudanã ndeles refletirá automaticamente na interface do usuário.
- Métodos: Funções que podem ser chamadas e utilizadas dentro da instância Vue para realizar diversas operações.
- Template(modelo): Define a estrutura do usuário, Pode ser um código HTML puro ou usar a sintaxe de template do Vue.
- Computed Properties(propriedades computadas): Dados derivados de outros dados. Eles são reativos e se atualizam automaticamente quando as dependências são modificadas.

## vue-loader

O Vue Loader funciona como um pré-processador para arquivos .vue. Quando você importa um arquivo .vue para o seu código JavaScript, o Vue Loader é acionado e executa uma série de transformações no arquivo.

Primeiro, o Vue Loader extrai o modelo HTML do arquivo .vue e o compila em uma função JavaScript que retorna o código HTML renderizado pelo componente. Em seguida, ele processa os estilos CSS, aplicando prefixos de fornecedores e resolvendo dependências entre estilos. Por fim, o Vue Loader compila o código JavaScript do componente, transformando-o em uma função que pode ser executada pelo navegador.

Essas transformações são realizadas de forma transparente para o desenvolvedor, permitindo escrever código Vue em um formato mais intuitivo e produtivo. O Vue Loader também oferece suporte a recursos avançados, como recarregamento a quente, que permite atualizar o código do componente em tempo real durante o desenvolvimento.

## Usando VSCode

Extensões que podem ser úteis ao usar VSCode ao desenvolver usando Vue.js:

- [Vetur](https://marketplace.visualstudio.com/items?itemName=octref.vetur)
- [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer)


