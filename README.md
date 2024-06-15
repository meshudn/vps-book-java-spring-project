Virtual Bookstore

It is a java based project developed using Microservice architecture.

## Service 00:
      gateway-service/
      │
      ├── src/main/java/com/example/gatewayservice/
      │   ├── config/
      │   ├── filter/                # Filters for logging, security, etc.
      │   └── controller/
      │
      ├── src/main/resources/
      │   ├── application.properties
      │   └── static/
      │
      ├── src/test/java/com/example/gatewayservice/
      │
      └── build.gradle or pom.

## Service 01: 
      book-catalog-service/
      │
      ├── src/main/java/com/example/bookcatalogservice/
      │   ├── config/
      │   ├── controller/
      │   ├── service/
      │   ├── repository/
      │   ├── model/
      │   ├── dto/
      │   └── event/
      │
      ├── src/main/resources/
      │   ├── application.properties
      │   └── static/
      │
      ├── src/test/java/com/example/bookcatalogservice/
      │
      └── build.gradle or pom.xml
