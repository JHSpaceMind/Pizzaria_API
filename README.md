![Finalizado](https://img.shields.io/badge/Status-Finalizado-brightgreen)
# API de Pizzaria 🍕 

Uma API RESTful para gerenciar pedidos em uma pizzaria, permitindo operações de CRUD (Criar, Ler, Atualizar, Excluir) nos pedidos.

## Funcionalidades

### 1. Obter Todos os Pedidos
- **Método**: `GET /pedidos`
- **Descrição**: Retorna uma lista de todos os pedidos cadastrados na pizzaria.

### 2. Obter Pedido por ID
- **Método**: `GET /pedidos/{id}`
- **Descrição**: Retorna os detalhes de um pedido específico pelo seu ID. Retorna um erro 404 se o pedido não for encontrado.

### 3. Obter Pedidos por Sabor
- **Método**: `GET /pedidos/sabor/{sabor}`
- **Descrição**: Retorna uma lista de pedidos que contêm um sabor específico. Isso permite que os clientes vejam todos os pedidos relacionados a um sabor.

### 4. Obter Pedidos por Cliente
- **Método**: `GET /pedidos/cliente/{cliente}`
- **Descrição**: Retorna todos os pedidos feitos por um cliente específico. Isso é útil para consultar o histórico de pedidos de um cliente.

### 5. Adicionar Pedido
- **Método**: `POST /pedidos`
- **Descrição**: Adiciona um novo pedido ao sistema. Retorna um status 201 se o pedido for criado com sucesso.

### 6. Alterar Pedido
- **Método**: `PUT /pedidos/{id}`
- **Descrição**: Atualiza os dados de um pedido existente. Retorna um status 200 se atualizado com sucesso, ou um erro 404 se o pedido não for encontrado.

### 7. Deletar Pedido
- **Método**: `DELETE /pedidos/{id}`
- **Descrição**: Remove um pedido do sistema pelo seu ID. Retorna um status 204 se excluído com sucesso, ou um erro 404 se o pedido não for encontrado.

## Tecnologias Utilizadas 🛠️
- ![Java](https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=java&logoColor=white)
- ![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=for-the-badge&logo=spring&logoColor=white)
- ![JPA](https://img.shields.io/badge/Hibernate-59666C?style=for-the-badge&logo=hibernate&logoColor=white)
- ![Banco de Dados](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)

## Como Usar
1. Clone o repositório.
2. Configure o banco de dados no arquivo de propriedades.
3. Execute a aplicação.
4. Use um cliente HTTP como Postman ou Insomnia para interagir com a API.

## Contribuição 🤝
Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou enviar pull requests.
