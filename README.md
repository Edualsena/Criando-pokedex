# 🕹️ Pokédex Vanilla JS

Uma Pokédex moderna, rápida e responsiva construída puramente com **HTML5, CSS3 e JavaScript (ES6+)**, consumindo dados da [PokeAPI](https://pokeapi.co/).



## 🎯 Objetivo
Este projeto foi desenvolvido com o propósito de consolidar conhecimentos em **JavaScript Assíncrono**. O desafio foi criar uma aplicação funcional que lidasse com centenas de requisições de API de forma performática, sem depender de bibliotecas externas ou frameworks.

## 🚀 Funcionalidades
- **Listagem Dinâmica:** Carregamento automático dos Pokémon conforme o scroll ou paginação.
- **Pesquisa em Tempo Real:** Filtro por nome ou número oficial.
- **Cores Dinâmicas:** O fundo de cada card muda de cor de acordo com o tipo principal do Pokémon (ex: fogo = vermelho, erva = verde).
- **Modais de Detalhes:** Clique num Pokémon para ver estatísticas detalhadas (HP, Ataque, Defesa, etc.).
- **Responsividade Total:** Interface adaptada para smartphones, tablets e desktops.

## 🛠️ Tecnologias e Conceitos Utilizados
- **HTML5 & CSS3:** Uso de Variáveis CSS (Custom Properties) e CSS Grid/Flexbox.
- **Fetch API:** Consumo de dados da PokeAPI.
- **Async/Await:** Gestão de código assíncrono para evitar o "Callback Hell".
- **Métodos de Array:** Uso de `.map()`, `.filter()` e `.reduce()` para manipulação de dados.
- **DOM Manipulation:** Criação dinâmica de elementos para garantir uma UI reativa.

## 🧠 Desafios Técnicos
O maior desafio deste projeto foi lidar com o facto de a PokeAPI exigir uma nova requisição para obter os detalhes de cada Pokémon individualmente. 
Para resolver o problema de performance, utilizei o `Promise.all()`, permitindo que todas as requisições de uma lista fossem feitas em paralelo, resultando num carregamento muito mais veloz do que o uso de um `for` loop comum.

