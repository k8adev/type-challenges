<!--info-header-start--><h1>Parseador de Query String <img src="https://img.shields.io/badge/-extremo-b11b8d" alt="extremo"/> <img src="https://img.shields.io/badge/-%23template--literal-999" alt="#template-literal"/></h1><blockquote><p>by Pig Fang <a href="https://github.com/g-plane" target="_blank">@g-plane</a></p></blockquote><p><a href="https://tsch.js.org/151/play/pt-BR" target="_blank"><img src="https://img.shields.io/badge/-Fazer%20o%20Desafio-3178c6?logo=typescript&logoColor=white" alt="Fazer o Desafio"/></a> &nbsp;&nbsp;&nbsp;<a href="./README.md" target="_blank"><img src="https://img.shields.io/badge/-English-gray" alt="English"/></a> </p><!--info-header-end-->

> Traduzido pelo Google, abra um PR para ajudar a melhorar a tradução.

É necessário implementar um analisador de nível de tipo para analisar a string de consulta de URL em um tipo literal de objeto.

Alguns requisitos detalhados:

- O valor de uma chave na string de consulta pode ser ignorado, mas ainda assim analisado como `true`. Por exemplo, `'key'` não tem valor, então o resultado do analisador é `{ key: true }`.
- As chaves duplicadas devem ser mescladas em uma. Se houver valores diferentes com a mesma chave, os valores deverão ser mesclados em um tipo de tupla.
- Quando uma chave tem apenas um valor, esse valor não pode ser agrupado em um tipo de tupla.
- Se valores com a mesma chave aparecerem mais de uma vez, deverá ser tratado como uma única vez. Por exemplo, `key=value&key=value` deve ser tratado apenas como `key=value`.

<!--info-footer-start--><br><a href="../../README.pt-BR.md" target="_blank"><img src="https://img.shields.io/badge/-Voltar-grey" alt="Voltar"/></a> <a href="https://tsch.js.org/151/answer/pt-BR" target="_blank"><img src="https://img.shields.io/badge/-Compartilhar%20suas%20Solu%C3%A7%C3%B5es-teal" alt="Compartilhar suas Soluções"/></a> <a href="https://tsch.js.org/151/solutions" target="_blank"><img src="https://img.shields.io/badge/-Conferir%20Solu%C3%A7%C3%B5es-de5a77?logo=awesome-lists&logoColor=white" alt="Conferir Soluções"/></a> <!--info-footer-end-->