# heroes-dio-tqi
API - Spring Webflux - Criando Gerenciador de Herois da Marvel e da DC em uma API reativa com Spring Boot
para o BootCamp da Dio-TqI

Utilizada por empresas como Netflix e Pivotal, junto com a library reativa Reactor que atualmente é mantida pela VmWare. Além disso, usamos o banco DynamoDb localmente para armazenar nossos dados e demonstrar como realizar testes unitários da API com Junit e como gerar documentações simples por meio do Postman e também do Swagger.

#Stack utilizada#

Java8
spring webflux
Spring data
dynamodb
junit
sl4j
reactor

Executar dynamo:
na pasta em que o jar está baixado: java -Djava.library.path=./DynamoDBLocal_lib -jar DynamoDBLocal.jar -sharedDb

para listar as tabelas criadas: aws dynamodb list-tables --endpoint-url http://localhost:8000

documentacao gerada pela aplicação: swagger: http://localhost:8080/swagger-ui-heroes-reactive-api.html

Postman

https://documenter.getpostman.com/view/18013280/UVR4M9nH
