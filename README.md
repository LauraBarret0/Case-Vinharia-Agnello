# Case da Vinheria Agnello - CheckPoint_1 Front-End

Este repositório contém o desenvolvimento de um projeto front-end baseado no case fictício da **"Vinheria Agnello"**, que visa a criação de uma aplicação web simples de uma vinheria familiar.

## 📘 Sobre o projeto

A Vinheria Agnello é uma empresa familiar com longa tradição no mercado de vinhos, reconhecida pela qualidade dos seus vinhos e pelo seu atendimento acolhedor. O projeto propõe desenvolver uma interface web que represente sua identidade, facilite o contato com seus clientes e destaque seus principais produtos e serviços.

A página conta com as seguintes seções:

- 🏰 **História da Vinheria**: Uma introdução sobre a origem, tradição e valores da Vinheria Agnello.
- 🍷 **Nossos Vinhos**: Um catálogo visual com alguns dos principais rótulos oferecidos pela vinheria.
- 🧀 **Harmonizações Sugeridas**: Recomendações de combinações entre vinhos e pratos, valorizando a experiência gastronômica.
- 📞 **Contato**: Uma área para que visitantes possam entrar em contato com a vinheria.

## 🎨 Efeitos Visuais

O projeto aplica uma variedade de efeitos visuais com o uso de CSS moderno, melhorando a interatividade e a experiência do usuário:

### 🔹 Pseudo-classes

- `:hover` em botões e links (como `.enviar`, `.filtrar`, `.adicionar`, `.sobrenome__link`) altera cor de fundo ou aplica sublinhado para indicar interatividade.
- `:active` e `:visited` personalizados em links externos (`.link_externo`) alteram a cor conforme o estado do link.
- `:focus` aplicado na `textarea` de mensagem (`.espacomensagem`) amplia sua altura e muda a cor da borda para dar destaque ao foco do usuário.

### 🔸 Pseudo-elementos

- `::selection` no texto da seção de história (`.historia__texto`) muda a cor de fundo e do texto ao selecionar trechos.
- `::first-letter` estiliza a primeira letra dos parágrafos da história, aumentando seu tamanho e aplicando negrito e cor personalizada.

### 🌀 Animações

- `@keyframes aparecer`: usado para animar elementos com `opacity`, aplicando efeito de fade-in suave.
- `.banner__titulo` e `.banner__texto` usam essa animação com diferentes durações (2s e 5s) ao carregar a página.

### 🔁 Transições e Transformações

- `.nav__item a:hover`: aplica `box-shadow` interno ao passar o mouse.
- `.sobrenome__link`, `.destaque__link`: utilizam `transform: scale(1.1)` ao passar o mouse para criar um leve efeito de zoom.
- `.destaque__img:hover`: aplica rotação de 45 graus, criando um destaque visual animado.

## 🚀 Tecnologias Utilizadas
<div align="left">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" height="40" alt="html5 logo" />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" height="40" alt="css3 logo" />
  <img width="12" />
</div>

## 📁 Estrutura do Projeto

```css
case-vinharia-agnello/
│
├── index.html
├── README.md
├── src/
│   ├── assets/
│   │   └── imgs/
│   ├── css/
│   │   └── style.css
│   │   └── efeitos.css
│   └── pages/
|       ├── vinhos/
│       ├── contato.html
│       ├── harmonizacao.html
|       ├── historia.html
│       ├── vinhos.html
```
---

## 👥 Integrantes

- Laura Barreto - RM561965
- Matheus Freitas Vieira - RM566198
- Natália Camargo - RM565769

## 🌐 Acesse o GitHub pages

🔗 [Clique aqui para acessar o GitHub pages](https://laurabarret0.github.io/Case-Vinharia-Agnello/)
