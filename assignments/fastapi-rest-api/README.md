# 📘 Assignment: Construindo APIs REST com FastAPI

## 🎯 Objective

Aprender a criar uma API RESTful utilizando o framework FastAPI em Python. O estudante irá praticar conceitos de rotas, métodos HTTP, manipulação de dados e resposta em formato JSON.

## 📝 Tasks

### 🛠️ Criar uma API de Gerenciamento de Itens

#### Description
Implemente uma API simples para gerenciar uma lista de itens (ex: produtos, tarefas, livros). A API deve permitir operações de criação, leitura, atualização e remoção (CRUD) de itens.

#### Requirements
Completed program should:

- Utilizar o framework FastAPI
- Implementar rotas para:
  - Listar todos os itens (GET)
  - Adicionar um novo item (POST)
  - Buscar um item por ID (GET)
  - Atualizar um item existente (PUT)
  - Remover um item (DELETE)
- Utilizar um dicionário ou lista em memória para armazenar os itens
- Retornar respostas em formato JSON
- Documentação automática disponível em `/docs`

##### Exemplo de execução
```bash
uvicorn main:app --reload
```
Acesse: http://localhost:8000/docs para testar a API interativamente.
