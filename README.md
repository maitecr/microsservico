# microsservico


Projeto desenvolvido durante o curso da Alura voltado para aprendizado sobre Microsserviços. 

Nele, foi trabalhos os conceitos e as práticas de:
(a) API: utilizando requisições HTTPs para desenvolvimento do CRUD e o MySQL enquanto banco de dados: atuando juntamente com as dependência do Lombok para utilizarmos suas anotações, otimizando a escrita de código; Model Mapper nos auxiliando no transporte de dados; e o MySQL Driver para estabelecer a conexão com o bando de dados;
(b) Migrations: foi utilizado o FlyWay para controle de versionamento dos bancos de dados;
(c) Service Discovery: dependência Eureka para que pudesse ser efetivada o serviço de descoberta;
(d) Load Balancer: criação de instância, a partir do próprio Eureka, para que pudessemos subir um mesmo microsserviço ao mesmo tempo;
(e) Gateway: novamente, jutamente com o Eureka, consegue-se construir esse serviço que irá centralizar os outros serviços em execução e, assim, consegue-se chamá-los a atráves da mesma porta;
(f) Comunicação síncrona: utilizando a dependência do Open Feign para que pudessemos estabelecer a comunicação síncrona;
(g) Circuit Breaker: caso haja um erro ao tentarmos estabelecer uma comunicação síncrona, usamos o Circuit Breaker para interromper a comunicação e evitar erros em cascata;
(h)Fallback: a partir do Fallback, podemos indicar outra ação ser executada, caso nossa comunicação tenha sido interrompida pelo circuit breaker.

