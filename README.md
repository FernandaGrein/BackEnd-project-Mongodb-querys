# MongoDb Project

Este foi o primeiro projeto em MongoDb que realizei na Trybe, nele trabalhei com os dados de um cardápio incluindo informações sobre os lanches como nome  e ingredientes, os valores nutricionais e dados de venda. 
Por meio de diversas query foi possível manipular todas as informações do banco, como contar os documentos pelo total ou por determinado parâmetro. Foram feitas diversas buscas de acordo com características dos lanches, bem como, há querys de manipulação dos arrays dentro de cada um. Também foi trabalhado com a adição e remoção de informações dentro de arrays e do próprio documento.

Para acessar este projeto clone o presente repositório, crie um container Mongo local e acesse o container, seguindo os passos abaixo: 
 - git clone git@github.com:FernandaGrein/BackEnd-project-Mongodb-querys.git
 - cd BackEnd-project-Mongodb-querys
 - docker run -d --name=nomeDoContainer -v "$PWD:/app" -p 27017:27017 mongo:5.0
 - docker exec -it nomeDoContainer bash
