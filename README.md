# ad-juster homework

Ad-juster's technical test

## Getting Started

After cloning the repo, use mvnw to build and package
To build execute :
```
./mvnw clean package
```

## Executing

You can execute the test by running the jar in the /target folder
```
java -jar homework-1.0.0.jar
```
This will launch Spring Boot locally and execute the assignment.

I decided to use an in-memory database so it can run stand alone without having to connect to a database.

If you decide to connect to a database, I also checked in the application.properties I used to connect to my local mysql database.

You can use that as a reference or change it to connect to your own database to push the data in.

After executing, a 'campaign.csv' file will be created in the folder where the jar file was executed.


## Built With

* [Java 8](http://www.oracle.com/technetwork/java/index.html)
* [Spring Boot](https://projects.spring.io/spring-boot/)
* [MySQL](https://www.mysql.com/)
* [H2](http://www.h2database.com/)
* [Maven](https://maven.apache.org/)

## Author

* **Joshua Kim**
