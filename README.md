<h1 style="text-align: center;">
  Plann.er Backend
</h1>

<p align="center">
  <a href="#project">Projeto</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#technologies">Tecnologias</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#usage">Utilização</a>
</p>

<h2 id='project'>Projeto</h2>

O backend desenvolvido para a aplicação "plann.er" durante o NLW Journey da Rocketseat é descrito na documentação da API. A aplicação utiliza Node.js e oferece uma série de endpoints para a gestão de planejamento de tarefas, incluindo criação, leitura, atualização e exclusão de tarefas. A API segue as especificações OpenAPI 3.0.0, permitindo fácil integração com diversas bibliotecas de clientes em várias linguagens de programação. A documentação detalha os métodos HTTP, parâmetros de entrada, e exemplos de resposta para cada endpoint.

Para mais detalhes, acesse a [documentação completa](https://nlw-journey.apidocumentation.com/reference).

<h2 id="technologies">Tecnologias</h2>

Este projeto foi desenvolvido com as seguintes tecnologias:

- [Prisma](https://www.prisma.io/)
- [TypeScript](https://www.typescriptlang.org/)
- [Node.js](https://nodejs.org/en/)
- [Fastify](https://fastify.dev/)
- [Zod](https://zod.dev/)
- [Nodemailer](https://nodemailer.com/)
- [Dayjs](https://day.js.org/)

<h2 id="usage">Executando o Back-end</h2>

```bash
# No BackEnd insira uma porta, as urls e o arquivo do banco de dados no arquivo .env vazio
  DATABASE_URL=
  API_BASE_URL=
  WEB_BASE_URL=
  PORT=

# Navegue até o diretório do BackEnd
$ cd plann-er-backend

# Instale as dependências necessárias
$ npm install

# Agora inicie o servidor do BackEnd
$ npm run dev
```