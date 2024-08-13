# Projeto de Banco de Dados E-commerce

Este repositório contém a modelagem de um banco de dados para um sistema de e-commerce, desenvolvido como parte de um desafio na DIO.

## Descrição do Projeto

O projeto consiste na criação de um modelo de banco de dados relacional para um sistema de e-commerce, abrangendo as principais operações necessárias para a gestão de produtos, pedidos, clientes, fornecedores, pagamentos e entregas.

## Estrutura do Banco de Dados

A modelagem foi feita utilizando diagramas de Entidade-Relacionamento (ER), conforme a imagem abaixo:

![eccommerce](https://github.com/user-attachments/assets/99f0f19e-3889-42fd-baf8-acedee92ad29)

### Entidades Principais

- **Cliente**: Armazena informações dos clientes, incluindo CPF para pessoas físicas e CNPJ para pessoas jurídicas.
- **Produto**: Contém detalhes dos produtos disponíveis no e-commerce.
- **Fornecedor**: Informações sobre os fornecedores dos produtos.
- **Pedido**: Registra os pedidos realizados pelos clientes, incluindo o status e descrição.
- **Entrega**: Detalhes sobre o processo de entrega dos pedidos, incluindo status, data prevista e código de rastreio.
- **Pagamento**: Métodos de pagamento utilizados para cada pedido, como cartão de crédito, débito, e PIX.
- **Estoque**: Gerenciamento dos produtos disponíveis em estoque.

### Relacionamentos

- **Cliente - Pedido**: Um cliente pode fazer múltiplos pedidos.
- **Pedido - Produto**: Um pedido pode conter múltiplos produtos.
- **Produto - Fornecedor**: Cada produto é fornecido por um fornecedor específico.
- **Produto - Estoque**: Relaciona os produtos ao estoque disponível.

## Tecnologias Utilizadas

- **Modelagem ER**: MySQL Workbench
- **Banco de Dados**: MySQL
