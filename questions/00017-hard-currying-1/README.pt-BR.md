<!--info-header-start--><h1>Currying 1 <img src="https://img.shields.io/badge/-dif%C3%ADcil-de3d37" alt="difícil"/> <img src="https://img.shields.io/badge/-%23array-999" alt="#array"/></h1><blockquote><p>by Anthony Fu <a href="https://github.com/antfu" target="_blank">@antfu</a></p></blockquote><p><a href="https://tsch.js.org/17/play/pt-BR" target="_blank"><img src="https://img.shields.io/badge/-Fazer%20o%20Desafio-3178c6?logo=typescript&logoColor=white" alt="Fazer o Desafio"/></a> &nbsp;&nbsp;&nbsp;<a href="./README.md" target="_blank"><img src="https://img.shields.io/badge/-English-gray" alt="English"/></a>  <a href="./README.zh-CN.md" target="_blank"><img src="https://img.shields.io/badge/-%E7%AE%80%E4%BD%93%E4%B8%AD%E6%96%87-gray" alt="简体中文"/></a>  <a href="./README.ja.md" target="_blank"><img src="https://img.shields.io/badge/-%E6%97%A5%E6%9C%AC%E8%AA%9E-gray" alt="日本語"/></a> </p><!--info-header-end-->

> Traduzido pelo Google, abra um PR para ajudar a melhorar a tradução.

> TypeScript 4.0 é recomendado neste desafio

[Currying](https://en.wikipedia.org/wiki/Currying) é a técnica de converter uma função que recebe vários argumentos em uma sequência de funções, cada uma com um único argumento.

Por exemplo:

```ts
const add = (a: number, b: number) => a + b
const three = add(1, 2)

const curriedAdd = Currying(add)
const five = curriedAdd(2)(3)
```

A função passada para `Currying` pode ter vários argumentos, você precisa digitá-la corretamente.

Neste desafio, a função curried aceita apenas um argumento por vez. Depois que todo o argumento for atribuído, ele deverá retornar seu resultado.

<!--info-footer-start--><br><a href="../../README.pt-BR.md" target="_blank"><img src="https://img.shields.io/badge/-Voltar-grey" alt="Voltar"/></a> <a href="https://tsch.js.org/17/answer/pt-BR" target="_blank"><img src="https://img.shields.io/badge/-Compartilhar%20suas%20Solu%C3%A7%C3%B5es-teal" alt="Compartilhar suas Soluções"/></a> <a href="https://tsch.js.org/17/solutions" target="_blank"><img src="https://img.shields.io/badge/-Conferir%20Solu%C3%A7%C3%B5es-de5a77?logo=awesome-lists&logoColor=white" alt="Conferir Soluções"/></a> <hr><h3>Desafios Relacionados</h3><a href="https://github.com/type-challenges/type-challenges/blob/main/questions/00014-easy-first/README.pt-BR.md" target="_blank"><img src="https://img.shields.io/badge/-14%E3%83%BBPrimeiro%20do%20Array-7aad0c" alt="14・Primeiro do Array"/></a>  <a href="https://github.com/type-challenges/type-challenges/blob/main/questions/00016-medium-pop/README.pt-BR.md" target="_blank"><img src="https://img.shields.io/badge/-16%E3%83%BBPop-d9901a" alt="16・Pop"/></a>  <a href="https://github.com/type-challenges/type-challenges/blob/main/questions/00462-extreme-currying-2/README.md" target="_blank"><img src="https://img.shields.io/badge/-462%E3%83%BBCurrying%202-b11b8d" alt="462・Currying 2"/></a> <!--info-footer-end-->