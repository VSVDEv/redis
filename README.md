# Getting Started

### Reference Documentation
For further reference, please consider the following sections:

* [Official Apache Maven documentation](https://maven.apache.org/guides/index.html)
* [Spring Boot Maven Plugin Reference Guide](https://docs.spring.io/spring-boot/docs/2.5.3/maven-plugin/reference/html/)
* [Create an OCI image](https://docs.spring.io/spring-boot/docs/2.5.3/maven-plugin/reference/html/#build-image)
* [Spring Web](https://docs.spring.io/spring-boot/docs/2.5.3/reference/htmlsingle/#boot-features-developing-web-applications)
* [Spring Data Redis (Access+Driver)](https://docs.spring.io/spring-boot/docs/2.5.3/reference/htmlsingle/#boot-features-redis)

### Guides
The following guides illustrate how to use some features concretely:

* [Building a RESTful Web Service](https://spring.io/guides/gs/rest-service/)
* [Serving Web Content with Spring MVC](https://spring.io/guides/gs/serving-web-content/)
* [Building REST services with Spring](https://spring.io/guides/tutorials/bookmarks/)
* [Messaging with Redis](https://spring.io/guides/gs/messaging-redis/)

## Run
 docker run --name rediss -p 6379:6379 -d redis

```json

POST /product HTTP/1.1
Host: localhost
Content-Type: application/json
Content-Length: 48

{"id":116,
"name":"test",
"qty":2, "price":1000}


GET /product/116 HTTP/1.1
Host: localhost

GET /product/113 HTTP/1.1
Host: localhost

POST /product/ HTTP/1.1
Host: localhost
Content-Type: application/json
Content-Length: 48

{"id":117,
"name":"test1",
"qty":1, "price":500}

GET /product/117 HTTP/1.1
Host: localhost

```
