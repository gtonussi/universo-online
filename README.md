# Teste front-end - UOL Produtos Digitais

<div style="display: flex; width: 100%; justify-content: center;">
 <img src="https://c.tenor.com/dp4wyZ0yRUcAAAAC/duke-nukem-gaming.gif" width="400"/>
</div>

<p style="text-align: center;">
  >>>> Coded by Giovanni Tonussi. Obrigado por conferir! Por favor leia as instruções abaixo: <<<<
</p>

### Infra:

Este projeto foi criado com ```next.js```. 
Mais sobre o framework: https://nextjs.org/

A estilização foi feita toda com ```styled-components```. 
Mais sobre a lib: https://styled-components.com/

Usei também algumas libs para aumentar a produtividade. São elas:

- ```axios``` para requisições a API.
- ```json-server``` para criar um server fake.

- ```react-hook-form``` para criação dos formulários.
- ```yup``` para validação dos formulários.

### IMPORTANTE: 

Como o endpoint foi configurado para não aceitar cross-origin, baixei o json e criei um server a partir dele. Dessa forma, o código foi criado para fazer requisições a uma API externa.

**Para criar o server, é necessário instalar o ```json-server```:**

- Abra um terminal/cmd na pasta do projeto
- Rode: *npm install -g json-server*
- Rode: *json-server --watch db.json*

**Deixar a porta 3000 livre :)**

Para rodar o projeto, são os típicos comandos do Next:

- Abra um terminal/cmd na pasta do projeto
- Rode: *yarn install*
- Crie um preview: *yarn dev*