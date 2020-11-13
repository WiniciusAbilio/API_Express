# API_Express
### Rotas

- `POST /produto`: A rota deve receber `nome` e `preco` dentro corpo de cadastrar um novo produto dentro de um array no seguinte formato: `{ nome: Celular, preco: 1290.35}`; 

- `GET /produto`: Rota que lista todos produtos;

- `PUT /produto/:id`: A rota deve alterar o nome ou/e o preço do produto com o `id` presente nos parâmetros da rota;

- `DELETE /produto/:id`: A rota deve deletar o produto com o `id` presente nos parâmetros da rota;

### Exemplo

Se eu chamar a rota `GET /produto` meu array de produtos deve ficar assim:

```js
[
  {
    nome: "Celular",
    preco: 1290.35,
    id: "1"
  }
];
```
