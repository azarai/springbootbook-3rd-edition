Learn to build your first Spring Boot 2.1 application with an actionable and hands-on approach.

This is the sample application for the pocket guide [Spring Boot 2: How To Get Started and Build a Microservice](http://codeboje.de/spring-boot-book/ "Spring Boot book") - third edition.

The pocket guide is available on [my site](http://codeboje.de/spring-boot-book/ "the Spring Boot book home").

# Parts

1. _spring-core-exercise_ contains the sample application for the Spring Core Beginners chapter
2. _spring-boot-microservice_ contains the sample microservice we build

# Running the Microservice

The microservice is using a Maven Multimodule setup. To build it completely, follow these steps.

After cloning the project run

```bash
cd spring-boot-microservice
```

```bash
mvn clean install
```

Change into the comment-store directory

```bash
cd comment-store
```

and finally run it:

```bash
mvn spring-boot:run
```
