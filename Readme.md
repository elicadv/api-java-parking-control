### Api Parking-Control

## Esta é uma aplicação em Java que implementa uma API com operações CRUD (Create, Read, Update, Delete) para gerenciar informações sobre vagas de estacionamento.

# Rotas

- Get geral - http://localhost:8080/parking-spot
* Retorna todas as vagas de estacionamento cadastradas na base de dados.

- Get id - http://localhost:8080/parking-spot/{id}
* Retorna a vaga de estacionamento correspondente ao ID informado.

- Post - http://localhost:8080/parking-spot
* Cria uma nova vaga de estacionamento na base de dados.

- Delete id - http://localhost:8080/parking-spot/{id}
* Remove a vaga de estacionamento correspondente ao ID informado da base de dados.

- Put id - http://localhost:8080/parking-spot/{id}
* Alterar informações correspondente ao ID informado da base de dados.