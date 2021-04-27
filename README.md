<h1 align="center">Podcastr 🎙🎤</h1>

<div align="center">
  <img src="https://ik.imagekit.io/jp1xbaqmsn6/1619529443137_dqY5xpXte6.png" alt="Podcastr logo" align="center">
</div>

## Índice
- [Introdução](#introdução)
- [Como usar](#como-usar)
- [Como clonar o repositório](#como-clonar-o-repositório)
- [Como iniciar o projeto](#como-iniciar-o-projeto)
- [Tecnologias utilizadas](#tecnologias-utilizadas)
- [Contato](#contato)

## Introdução
🎤🎤🎤

O Podcastr é um projeto feito com tecnologias atuais que estão sendo usadas por grandes empresas. O Podcastr, possibilita o 
usuário ouvir um Podcast que vem de elementos nativos do HTML,
como a tag ```<audio>```. O design é minimalista mas sofisticado. As páginas têm velocidade maior do que as páginas convencionais, 
por usar conceitos como [SSG](https://www.netlify.com/blog/2020/04/14/what-is-a-static-site-generator-and-3-ways-to-find-the-best-one/) 
(<i>static site generator</i>) e [SSR](https://medium.com/techbloghotmart/o-que-%C3%A9-server-side-rendering-e-como-usar-na-pr%C3%A1tica-a840d76a6dca) 
(<i>server side rendering</i>). Este projeto não tem um [API](https://pt.wikipedia.org/wiki/Interface_de_programa%C3%A7%C3%A3o_de_aplica%C3%A7%C3%B5es) 
de fato, pois usa-se uma biblioteca que cria uma [API](https://pt.wikipedia.org/wiki/Interface_de_programa%C3%A7%C3%A3o_de_aplica%C3%A7%C3%B5es) apartir de um arquivo 
[JSON](https://www.devmedia.com.br/o-que-e-json/23166#:~:text=JSON%20%C3%A9%20basicamente%20um%20formato,posso%20usar%20com%20JavaScript%20correto%3F).

## Como usar
🦶 a 🦶

Para usar o Podcastr, basta clicar no botão de play que está sempre à direita do podcast que você deseja ouvir.
<div align="space-between">
  </img src="https://ik.imagekit.io/jp1xbaqmsn6/plays_podcastr_PtQzrdV3_.png" alt="Onde clicar" width="500" height="300">
  <img src="https://media.giphy.com/media/pwaYzTQcLAnIOLvjHi/giphy.gif" alt="como usar gif" width="500" height="300">
</div>


Podemos também ver o detalhe de um podcast apenas clicando em seu título, lembrando que quando estamos ouvindo um podcast em específico
não podemos usar a funcionalidade aleatório.
<div align="center">
  <img src="https://media.giphy.com/media/zBxzwGSay4vX5bbRR4/giphy.gif" alt="detalhe do podcast" width="600" height="400">
</div>

## Como clonar o repositório
📄➡📃

Para clonar o repositório, execute os seguintes comandos em seu terminal:
```bash
git clone https://github.com/Allan28818/NLW-5-ReactJS.git
``` 

Agora entre na pasta do projeto com:
```bash
cd podcastrnext
```

## Como iniciar o projeto
⏯

O nosso projeto tem uma "<i>fake</i>" [API](https://pt.wikipedia.org/wiki/Interface_de_programa%C3%A7%C3%A3o_de_aplica%C3%A7%C3%B5es), que vem de um arquivo em 
[JSON](https://www.devmedia.com.br/o-que-e-json/23166#:~:text=JSON%20%C3%A9%20basicamente%20um%20formato,posso%20usar%20com%20JavaScript%20correto%3F), então recomendo fortemente iniciar a API antes do front-end,
principalmente em produção. Então execute:
```bash
# Para quem usa npm
npm run server

# Para quem usa yarn
yarn server
```

Com o servidor no ar podemos iniciar o projeto em dois modos, produção ou desenvolvimento.
- Desenvolvimento: recomendado para quando você ainda está construindo o projeto e ele ainda não está no ar. 
Para iniciar esse modo execute: 
```bash
# Para quem usa npm
npm run dev

# Para quem usa yarn
yarn dev
```

- Produção: recomendado para simular (ou aplicar realmente em produção) um cenário onde o projeto estaría no ar. 
Neste modo o <i>prefetch</i> e SSG estão habilitados.
  - Primeiro temos que carregar os dados do projeto com o seguinte comando:
  ```bash
    # Para quem usa npm
    npm run build

    # Para quem usa yarn
    yarn build
  ```
  
   - Agora podemos iniciar o projeto com:
   ```bash
    # Para quem usa npm
    npm run start

    # Para quem usa yarn
    yarn start
  ```
  
Quando tiver feito tudo que foi listado, clique [aqui](http://localhost:3000) para acessar o projeto (localhost:3000).
  
  
## Tecnologias utilizadas
🖥💻🖱

Neste projeto utilizamos as seguines tecnologias:
  - [HTML](https://developer.mozilla.org/pt-BR/docs/Web/HTML) 🧡
  - [JavaScript](https://www.javascript.com/) 💛
  - [React](https://pt-br.reactjs.org/docs/getting-started.html) ⚛
  - [Next](https://nextjs.org/docs/getting-started) ⏭
  - [TypeScript](https://www.typescriptlang.org/docs/) 💙
  - [Axios](https://www.npmjs.com/package/axios) 🔗
  - [Date FNS](https://date-fns.org/docs/Getting-Started) 📆
  - [RC - slider](https://www.npmjs.com/package/rc-slider) 📹
  - [Sass](https://sass-lang.com/documentation) 💄👓
  - [JSON-server](https://www.npmjs.com/package/json-server) 🖥
  - e mais...
  
  ## Contato
  📲
  
  Para entrar em contato comigo, ou acompanhar meu progresso na programação veja os itens abaixo:
  - [x] [Linkedin](https://www.linkedin.com/in/allan-julie-b535811b4)
  - [x] [Instagram](https://www.instagram.com/allan120699/)
  - [x] Telefone: (61) 9 8410-3320
  - [x] E-mail: allanzinhofontes@gmail.com
  
  
  
  
