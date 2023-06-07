# api-produto
# API de Produtos  Esta é uma API simples para gerenciar produtos em um sistema. Ela permite listar, retornar detalhes e adicionar produtos.  ## Recursos  ### Listar produtos  Retorna a lista de produtos disponíveis.

Tecnologias utilizadas
Java
Spring Boot

GET /produtos

Como executar a aplicação
Clone este repositório.
Importe o projeto em uma IDE Java.
Execute a classe Application.java.
A API estará disponível em http://localhost:8080

Sinta-se à vontade para explorar e utilizar esta API para o gerenciamento de produtos em seu sistema

### Exemplo de resposta:

```json
[
  {
    "id": 1,
    "nome": "Mackbook",
    "preco": 4000.0,
    "departamento": {
      "id": 1,
      "nome": "Tecnologia"
    }
  },
  {
    "id": 2,
    "nome": "Pc Gamer",
    "preco": 5000.0,
    "departamento": {
      "id": 1,
      "nome": "Tecnologia"
    }
  },
  {
    "id": 3,
    "nome": "Mackbook",
    "preco": 3000.0,
    "departamento": {
      "id": 2,
      "nome": "Pet"
    }
  }
]
