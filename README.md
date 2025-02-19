# blog-api

API para estudo de testes de API.

Passos para executar a API:

1. Execute o comando `npm i` ou `yarn`
2. Execute o comando `yarn start` ou `npm start`

Após executar a API, é possível acessar a documentação por meio da url:

```
http://localhost:3000/docs
```

npm i -g newman

newman run nome_do-arquivo

npm i -g newman-reporter-htmlextra

newman run blog_api_endpoints.postman_collection.json --iteration-count 10 (bai fazer 10 vezes o script)

newman run blog_api_endpoints.postman_collection.json -r htmlextra


