# PHP - Tria Software

A necessidade é desenvolver uma API RESTFul para o gerenciamento de pedidos de um **E-comerce** utilizando o framework Laravel/Lúmen.

## Instruções para entrega

* Faça um fork desse repositório.
* Crie um README.
* Envie um email com o link do seu repositório para RH

## Sobre o projeto

A API Restful deve contemplar os módulos **Comprador**, **Produto** e **Checkout**, sendo que cada um deverá conter endpoints.

As tabelas devem ser criadas usando os **Migrations**
A Autenticação deve ser feita usando a própria estrutura do framework com autenticação JWT

## Requisitos

* Não devem existir dois clientes com o mesmo email.
* O produto deve possuir foto.
* Os dados devem ser validados.
* O sistema deve conter uma série de tipos de produtos já definidos.
* O pedido deve contemplar N produtos.
* O cliente pode contemplar N pedidos.
* Após a criação do pedido o sistema deve disparar um email para o cliente contendo os detalhes do seu pedido.
* Padronização PSR
* Utilizar CamelCase
* SOLID

## Requisitos adicionais

* Testes unitários.
* Dockerizar a aplicação

## Critérios de avaliação

* Readme.
* Docker.
* Framework.
* Organização do código.
* PSR.
* Migrations.
* Seeds
* Testes Uniários.
