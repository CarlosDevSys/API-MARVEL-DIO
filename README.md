# API-MARVEL-DIO
Projeto de api backend em Java com tabela de herois com operações de GET,POST e DELETE utilizando SPRINGBOOT, POSTMAN, SWAGGER, AWSCLI, DynamoDB, SPRINGWEBFLUX, SPRING DATA.

## Projeto do  TQI BootCamp Digital Innovation One 

Projeto de uma API REST Reativa Java de cadastro de heróis da Marvel e DC.

#### Stack utilizada
* Java8
* spring webflux
* Spring data
* Dynamodb
* Junit
* Sl4j
* Reactor

### Postman DOC.
 https://documenter.getpostman.com/view/16381890/UVC8Ckxi
 
 ### SWAGGER DOC.
Documentacao gerada pela aplicação: swagger: http://localhost:8080/swagger-ui.html
 
 ### Executar dynamo:
na pasta em que o jar está baixado abrir um prompt e executar: java -Djava.library.path=./DynamoDBLocal_lib -jar DynamoDBLocal.jar -sharedDb

para listar as tabelas criadas apos iniciar o banco execute em um prompt: aws dynamodb list-tables --endpoint-url http://localhost:8000

### Imagens do projeto
Documentacao gerada pela aplicação: swagger:

![img](https://github.com/CarlosDevSys/API-MARVEL-DIO/blob/main/images/Screenshot_20211112_203151.png)

Documentação gerada pelo Postman:

![img](https://github.com/CarlosDevSys/API-MARVEL-DIO/blob/main/images/postman.png)
 


