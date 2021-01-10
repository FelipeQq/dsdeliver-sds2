<p align="center">
  <a href="https://felipequeiroz-sds2.netlify.app/">
    <img src="https://github.com/FelipeQq/assets/blob/main/logo.svg" height="150" width="175" alt="Logo da DS Delivery" />
  </a>
</p>

<h1 align="center">DS Delivery</h1>
<p align="center">Projeto realizado durante a Semana DevSuperior 2.0</p>

<p align="center">
 <a href="#-sobre">Sobre</a> •
 <a href="#tecnologias-utilizadas">Tecnologias</a> • 
 <a href="#-Execução-do-projeto">Execução do Projeto</a>
</p>

## Layout WEB
![GIF 1](https://github.com/FelipeQq/assets/blob/main/video.gif)

# Sobre

<p>O DS Delivery tem por objetivo criar um sistema capaz de realizar pedidos em uma pizzaria fictícia. Durante o desenvolvimento foi criada uma 
API com quatros métodos:</p>

- GET /orders: retorna todos os pedidos do sistema de banco de dados que ainda estão pendentes;
- GET /products: retorna todos os produtos disponíveis para a compra;
- POST /orders: envia todas as informações do pedido que o cliente fez para o banco de dados;
- PUT /orders/{id}/delivered: atualiza o status do pedido para entregue.

<p>A landing page é composta por uma frase de efeito, uma imagem e um botão que levará o usuário à tela responsável pelo pedido do cliente, que, por sua vez, é uma
página que possui as orientações para o cliente, a lista de produtos, um mapa para obter a localização do usuário e o botão para confirmar o pedido.</p>

# Tecnologias utilizadas

## Back end
- Java
- Spring Boot
- JPA

## Front end
- HTML / CSS / JS / TypeScript
- ReactJS

# Execução do Projeto

## Back end
Pré requisitos: Java 11

```bash
# clonar repositório
git clone https://github.com/FelipeQq/dsdeliver-sds2.git

# entrar na pasta do projeto backend
cd backend

# executar projeto
.mvnw spring-boot:run
```

## Front end

```bash
# clonar repositório
git clone https://github.com/FelipeQq/dsdeliver-sds2.git

# entrar na pasta do projeto front end
cd front-web

# instalar dependências
npm install 

# executar projeto
npm start
```

# Autor

Felipe Queiroz

https://www.linkedin.com/in/felipe-queiroz-384b13187/


<br>
<br>
<br>
<a href="https://github.com/washingtonsoares" target="_new">
  <img src="https://img.shields.io/badge/-Washington%20Soares%20Braga-000000?style=flat-square&labelColor=000000&logo=github&logoColor=white"/>
</a>
<a href="https://github.com/acenelio" target="_new">
  <img src="https://img.shields.io/badge/-Nelio Alves-000000?style=flat-square&labelColor=000000&logo=github&logoColor=white"/>
</a>
