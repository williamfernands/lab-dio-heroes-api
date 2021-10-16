# lab-dio-heroes-api
desenvolvendo uma API de gerenciamento de heróis utilizando Spring WebFlux, Reactor, e utilizando o banco DynamoDB, realizando testes unitários da API com Junit e como gerar documentações simples por meio do Postman e também do Swagger.

## Stack utilizada

  * Java8
  * spring webflux
  * Spring data
  * dynamodb
  * junit
  * swagger
  * reactor
  * aws cli

### Executar dynamo: 

 na pasta em que o jar está baixado: java -Djava.library.path=./DynamoDBLocal_lib -jar DynamoDBLocal.jar -sharedDb
 
para listar as tabelas criadas:  aws dynamodb list-tables --endpoint-url http://localhost:8000


documentacao gerada pela aplicação: swagger: http://localhost:8080/swagger-ui-heroes-reactive-api.html
