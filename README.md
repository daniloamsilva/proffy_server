# Proffy Server

Projeto em Node.js desenvolvido na Next Level Week #2 da Rocketseat. Esta API integra uma aplicação chamada Proffy, uma plataforma que conecta alunos e professores.

O repositório da versão web pode ser encontrado [aqui](https://github.com/daniloamsilva/proffy_web), e a versão mobile [aqui](https://github.com/daniloamsilva/proffy_mobile).

## Como rodar o projeto?

Primeiro instalamos nossas dependências
```bash
yarn install
```
... depois executamos a migration para criar nossas tabelas
```bash
yarn knex:migrate
```
... e rodamos a aplicação.
```bash
yarn start
```

## Rotas

```javascript
// Aulas
GET   /classes  // Retorna os professores disponíveis dentro do filtro
POST  /classes  // Cria uma aula com os parâmetros passados por um professor

// Conexões
GET   /connections  // Retorna o número de conexões em alunos e professores
POST  /connections  // Adiciona mais uma conexão
```
