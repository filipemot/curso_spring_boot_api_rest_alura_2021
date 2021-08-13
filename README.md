# Curso SpringBoot Api Rest - Alura - Agosto - 2021
URL: https://cursos.alura.com.br/course/spring-boot-api-rest

**Conceitos Abordados:**

- Um resumo da história e evolução do Spring;
- Que, para criar um projeto com Spring Boot, utilizamos o Spring Initialzr, através do site https://start.spring.io;
- Como importar um projeto com Spring Boot na IDE Eclipse;
- Como é o pom.xml de uma aplicação que utiliza o Spring Boot;
- Que, para inicializar o projeto com Spring Boot, devemos utilizar a classe com o método main;
- Que, para criar um controller, utilizamos as anotações @Controller e @RequestMapping.
- Sobre a API que desenvolveremos ao longo do curso e sobre as classes de domínio dela;
- Que, para um método no controller não encaminhar a requisição a uma página JSP, ou Thymeleaf, devemos utilizar a anotação @ResponseBody;
- Que o Spring, por padrão, converte os dados no formato JSON, utilizando a biblioteca Jackson;
- Que, para não repetir a anotação @ResponseBody em todos os métodos do controller, devemos utilizar a anotação @RestController;
- Que, para não precisar reiniciar manualmente o servidor a cada alteração feita no código, basta utilizar o módulo Spring Boot DevTools;
- Que não é uma boa prática retornar entidades JPA nos métodos dos controllers, sendo mais indicado retornar classes que seguem o padrão DTO (Data Transfer Object);
- Os principais conceitos sobre o modelo arquitetural REST, como recursos, URIs, verbos HTTP, Representações e comunicação stateless.