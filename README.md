
# Todo API

API para gerenciamento de tarefas


## Documentação da API

#### Retorna todas as tarefas

```http
  GET /todo
```
#### Insere uma nova tarefa

```http
  POST /todo
  
    | Parâmetro   | Tipo       | Descrição                           |
    | :---------- | :--------- | :---------------------------------- |
    | `title` | `string` | **Obrigatório**. Descrição da tarefa      |
    | `done` | `string` | **Opcional**. Marca a tarefa como feita    |
```
#### Atualiza uma tarefa

```http
  PUT /todo/${id}

    | Parâmetro   | Tipo       | Descrição                           |
    | :---------- | :--------- | :---------------------------------- |
    | `title` | `string` | **Opcional**. Descrição da tarefa         |
    | `done` | `string` | **Opcional**. Marca a tarefa como feita    |
```
#### Deleta uma tarefa

```http
  DEL /todo/${id}
```


## Autor

- [@victorlima](https://www.github.com/victorl1ma)


## Variáveis de Ambiente

Para rodar esse projeto, você vai precisar adicionar as seguintes variáveis de ambiente no seu .env

`PG_DB` : `Nome do banco`

`PG_USER` : `Nome de usuário do banco`

`PG_PASSWORD` : `Senha do banco`




