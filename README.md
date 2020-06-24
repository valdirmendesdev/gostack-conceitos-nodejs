<img alt="GoStack" src="https://storage.googleapis.com/golden-wind/bootcamp-gostack/header-desafios.png" />

<h3 align="center">
  Desafio 02: Conceitos do Node.js
</h3>

<blockquote align="center">“Não espere para plantar, apenas tenha paciência para colher”!</blockquote>

<p align="center">
  <a href="https://rocketseat.com.br">
    <img alt="Made by Valdir Mendes" src="https://img.shields.io/badge/made%20by-Valdir%20Mendes-%2304D361">
  </a>

  <img alt="License" src="https://img.shields.io/badge/license-MIT-%2304D361">

  <a href="https://github.com/valdirmendesdev/gostack-conceitos-nodejs/stargazers">
    <img alt="Stargazers" src="https://img.shields.io/github/stars/valdirmendesdev/gostack-conceitos-nodejs?style=social">
  </a>
</p>

<p align="center">
  <a href="#rocket-sobre-o-desafio">Sobre o desafio</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#calendar-entrega">Entrega</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#memo-licença">Licença</a>
</p>

## :rocket: Sobre o desafio

Nesse desafio, foi proposto criar uma aplicação para treinar o que foi aprendido no módulo de conceitos no Node.js!

A ideia era desenvolver uma aplicação para armazenar repositórios de um portfólio. A aplicação precisava permitir a criação, listagem, atualização e remoção dos repositórios, e além disso permitir que os repositórios possam receber "likes".

### Rotas da aplicação

A aplicação desenvolvida possui as seguintes rotas:

- **`POST /repositories`**: Permite cadastrar um novo repositório. A rota deve receber `title`, `url` e `techs` dentro do corpo da requisição em json, sendo a URL o link para o github desse repositório.

- **`GET /repositories`**: Permite listar todos os repositórios;

- **`PUT /repositories/:id`**: Permite alterar os campos `title`, `url` e as `techs` de um repositório já cadastrado e identificado pelo `id` presente nos parâmetros da rota;

- **`DELETE /repositories/:id`**: A rota permite deletar um repositório com o `id` presente nos parâmetros da rota;

- **`POST /repositories/:id/like`**: A rota permite aumentar o número de likes do repositório específico escolhido através do `id` presente nos parâmetros da rota, a cada chamada dessa rota, o número de likes deve será aumentado em 1;

## :running: Rodando a aplicação

Para executar a aplicação, clone o repositório desse projeto, entre na pasta do projeto e instale as dependências com o seguinte comando no terminal:

```bash
yarn
```

Para rodar a aplicação, execute o seguinte comando no terminal:

```bash
yarn dev
```

Para rodar os testes automatizados, execute o seguinte comando no terminal:

```bash
yarn test
```

## :memo: Licença

Esse projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.