# App_Docker-Game-Old
📦 Aula de Docker – Aplicação Web com Jogo da Velha

Este repositório foi criado como parte de uma aula introdutória sobre Docker, com o objetivo de apresentar, de forma prática, os conceitos básicos de containerização de aplicações.

A aplicação utilizada como exemplo é um Jogo da Velha (Tic-Tac-Toe) desenvolvido com HTML, CSS e JavaScript, executado em um container Docker e acessível através do navegador.

🎯 Objetivos da Aula

Compreender o que é Docker e para que ele é utilizado

Criar um arquivo Dockerfile

Construir uma imagem Docker

Executar um container

Utilizar mapeamento de portas

Acessar uma aplicação web rodando dentro de um container

🛠️ Tecnologias Utilizadas

Docker

HTML5

CSS3

JavaScript

Servidor web (Nginx)

🚀 Como Executar a Aplicação

Clone este repositório:

git clone https://github.com/seu-usuario/seu-repositorio.git


Acesse a pasta do projeto:

cd seu-repositorio


Construa a imagem Docker:

docker build -t jogo-da-velha .


Execute o container:

docker run -p 8080:80 jogo-da-velha


Acesse no navegador:

http://localhost:8080
