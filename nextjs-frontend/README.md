# Sistema de Venda de Ingressos

## Descrição

Repositório do FrontEnd da aplicação feito em Next.js

## Rodar a aplicação

Dentro da pasta `next-frontend` execute o comando abaixo para rodar o container `Docker`:
```
docker compose up
```

Quando o container estiver pronto, precisamos acessar o container do `nextjs` e executar a aplicação:

```
// entrar no container:
docker compose exec nextjs bash

// instalar as dependências:
npm install

// executar a aplicação:
npm run dev

```
