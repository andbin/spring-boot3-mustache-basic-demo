<a name="">![Java 17](https://img.shields.io/badge/Java-17-cd853f "Java 17")</a>
<a name="">![Spring Boot 3.0.2](https://img.shields.io/badge/Spring%20Boot-3.0.2-6db33f "Spring Boot 3.0.2")</a>
<a name="">![Built with Apache Maven](https://img.shields.io/badge/Built%20with-Apache%20Maven-f76504 "Built with Apache Maven")</a>
<a name="">![MIT License](https://img.shields.io/badge/License-MIT-1081c1 "MIT License")</a>

# Spring Boot 3 &ndash; Mustache Basic Demo

This is a basic demo project that shows how to use **[Mustache](https://mustache.github.io)** (using [JMustache](https://github.com/samskivert/jmustache)) with **[Spring Boot](https://spring.io/projects/spring-boot) 3**.

## License

This project is released under the **MIT License**, a very *permissive* free software license.

See the full text of the license: **[LICENSE.txt](LICENSE.txt)**

## How to build and run the application

You can build and run the application in different ways (depending on your environment and/or IDE).

#### 1) Using Maven to build a &ldquo;fat&rdquo; JAR that is easy to run

From command line (in project's main directory):
* run `mvn package`
* go into the `target/` directory
* run `java -jar spring-boot3-mustache-basic-demo.jar`

#### 2) Using Maven to directly build&run the application

From command line (in project's main directory):
* run `mvn spring-boot:run`

#### 3) Using the Eclipse IDE

* import the project (&ldquo;File&rdquo; -> &ldquo;Import...&rdquo; then &ldquo;Existing Maven Projects&rdquo; etc...)
* build the project (if &ldquo;Build Automatically&rdquo; is not active)
* locate the `SpringBoot3MustacheBasicDemoApp` class and then &ldquo;Run As&rdquo; -> &ldquo;Java Application&rdquo;

**Note**: other IDEs (e.g. NetBeans, IntelliJ IDEA) can also be used, the import procedure may be very similar.

## How to use the application

Once the application is running, point your preferred browser to [http://localhost:8080](http://localhost:8080). You should see a simple page showing some version informations.
