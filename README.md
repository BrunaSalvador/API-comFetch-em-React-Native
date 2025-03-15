# API-comFetch-em-React-Native
Este projeto é uma API construído com Node.js e Express. Ele também utiliza o Fetch para fazer requisições HTTP.

A configuração inicial foi feita com o comando npm init, que gerou automaticamente o arquivo package.json, contendo as dependências do projeto. A principal dependência instalada é o Express, que facilita a criação de servidores e APIs. Além disso, o projeto faz uso do Fetch para realizar requisições HTTP de forma assíncrona.

No arquivo index.js, um servidor básico foi configurado usando o Express. O servidor responde a requisições GET na rota raiz (/), retornando a mensagem "API funcionando!" como confirmação de que está ativo. A aplicação roda localmente na porta 3000 e pode ser acessada em http://localhost:3000.

Para rodar a API, basta executar o comando node index.js no terminal. Isso iniciará o servidor, que ficará aguardando as requisições. Você pode testar a API acessando o endereço no navegador ou utilizando ferramentas como Postman, curl ou o Fetch diretamente no código JavaScript.

Este repositório oferece uma estrutura inicial para quem deseja começar a desenvolver APIs com Node.js, Express e Fetch, sendo fácil de expandir com novas funcionalidades, como novas rotas, autenticação e integração com bancos de dados, conforme a necessidade do projeto.
