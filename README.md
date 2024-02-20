# Sistema de Gerenciamento de Tarefas

Este é um sistema de gerenciamento de tarefas desenvolvido em Node.js com Express e MongoDB.

## Funcionalidades

- Permite aos usuários criar, atualizar e excluir tarefas.
- Define lembretes e prioridades para as tarefas.
- Facilita a organização e gerenciamento de tarefas pessoais ou de equipe.

## Tecnologias Utilizadas

- Node.js
- Express
- MongoDB
- Mongoose

## Configuração

1. Clone o repositório

2. Instale as dependências:
   cd sistema-gerenciamento-tarefas
   npm install

3. Configure o banco de dados MongoDB:

- Certifique-se de que o MongoDB está instalado e em execução na sua máquina.
- Altere a URI de conexão com o MongoDB no arquivo `config.js`, se necessário.

4. Inicie o servidor:
   npm start

5. Acesse o sistema no seu navegador:
   http://localhost:3000

## Endpoints da API

- `GET /api/tasks`: Retorna todas as tarefas.
- `POST /api/tasks`: Cria uma nova tarefa.
- `GET /api/tasks/:id`: Retorna uma tarefa específica.
- `PUT /api/tasks/:id`: Atualiza uma tarefa existente.
- `DELETE /api/tasks/:id`: Exclui uma tarefa.
