# Database queries challenge

Desafio 03 do conteúdo estudado nas aulas do Chapter III da trilha de NodeJS do Bootcamp Ignite da Rocketseat

## :hammer_and_wrench: Ferramentas

- [docker](https://docs.docker.com/)
- [nodejs](https://nodejs.org/en/docs/)
- [typescript](https://www.typescriptlang.org/)
- [ts-jest](https://www.npmjs.com/package/ts-jest)
- [jest](https://jestjs.io/pt-BR/)

## :desktop_computer: Padronização de código

- [Prettier](https://prettier.io/)

## :rocket: Executando o projeto

```bash
// Instale as dependências

yarn install

// Se você não possui um container do Docker rodando o Postgres, é possível criá-lo com seguinte comando:

docker run --name ignite-challenge-database-queries -e POSTGRES_DB=queries_challenge -e POSTGRES_PASSWORD=docker -p 5432:5432 -d postgres

// Concluindo a instalação rode

yarn test
```

### :heavy_check_mark: Testes da aplicação

UsersRepository

- [x] Should be able to find user with games list by user's ID
- [x] Should be able to list users ordered by first name
- [x] Should be able to find user by full name

GamesRepository

- [x] Should be able find a game by entire or partial given title
- [x] Should be able to get the total count of games
- [x] Should be able to list users who have given game id
