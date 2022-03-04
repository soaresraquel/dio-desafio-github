# O que é Spring?

É uma plataforma com diversos recursos para construção de aplicativos Java, facilitando assim o desenvolvimento em Java EE com módulos que facilitam a construção de softwares reduzindo tempo de desenvolvimento.



## Spring Framework

<img src = "https://docs.spring.io/spring-framework/docs/5.0.0.M5/spring-framework-reference/html/images/spring-overview.png">

## Beans

Um bean se trata de um objeto que é instanciado, montado e gerenciado por um container do Spring através de Inversão de Controle (IoC) e Injeção de Dependências (DI).



### Configurando

É possível configurar um Bean de duas formas: por arquivos XML ou através de anotações.

Em XML seria preciso definir a tag <bean> dentro de uma tag principal <beans> passando o path da classe assim o Spring saberá quais classes gerenciar a criação de instâncias e a injeção de dependências.



## Inversão de Controle

Inversão de Controle (ou IoC - Inversion of Control) é um processo onde se inverte o fluxo de comando de um programa. É uma ideia de desacoplar ou remover dependências do objeto e fornecer controle para outra camada. Este objeto delega a tarefa de construir dependências para um contêiner IoC.



## Inversão de Dependência 

A Injeção de Dependência (ou DI - Dependency Injection) define quais classes serão instanciadas e onde serão injetadas quando for necessário. Existem 3 formas de aplicar o DI, por injeção de construtor, setter e interface. O Spring Framework aplica a IoC quando necessário também utilizando o DI.



# Spring Boot

É uma extensão do Spring, que utiliza do Spring Framework para iniciar uma aplicação de forma simples e rápida, sem se preocupar com configurações complexas como, por exemplo, o Tomcat.



### Componentes base:

+ Spring Boot Starter;
+ Spring Boot Auto-Configuration;
+ Spring Boot Actuator;



## Principais dependências e bibliotecas

+ Swagger

É um projeto open source com diversas ferramentas utilizadas para desenvolver APIs com as especificação OpenAPI Specification (OAS), uma especificação para descrever, produzir, consumir e visualizar serviços de uma API REST. Com o OAS você poderá descrever recursos, URIs, modelo de dados, métodos HTTP aceitos e códigos de resposta.



+ Feign

É um cliente de serviço web declarativo (cliente HTTP) desenvolvido pela Netflix e um dos mais populares do Spring Cloud Component. Com ele é possível criar clientes API HTTP no java de forma mais simples para chamar/consumir os serviços REST, utilizando anotações.



# Spring Boot Test

Facilita o desenvolvimento de testes de unidade e integração com o Spring Boot Test, um recurso bastante utilizado no desenvolvimento de aplicações java para testar comportamentos do código e regras do negócio.

Para utilizarmos precisamos usar spring-boot0starter-test, que importa os módulos de teste Spring Boot, bem como JUnit Jupiter, AssertJ, Hamcrest e várias outras bibliotecas úteis.
