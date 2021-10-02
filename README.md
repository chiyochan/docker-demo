# docker-demo
# Getting Started

### Example from https://www.youtube.com/watch?v=FlSup_eelYE
* User Spring Tool Suite (STS) instead of IntelliJ Idea
* Generated the project from within STS, instead of Spring initializer
* Useful docker commands
docker -v
docker info
docker build -f Dockerfile -t spring-boot-docker .
docker images
docker run -p 8085:8085 spring-boot-docker
docker ps
docker stop gallant_montalcini

### Reference Documentation
For further reference, please consider the following sections:

* [Official Gradle documentation](https://docs.gradle.org)
* [Spring Boot Gradle Plugin Reference Guide](https://docs.spring.io/spring-boot/docs/2.5.5/gradle-plugin/reference/html/)
* [Create an OCI image](https://docs.spring.io/spring-boot/docs/2.5.5/gradle-plugin/reference/html/#build-image)
* [Spring Web](https://docs.spring.io/spring-boot/docs/2.5.5/reference/htmlsingle/#boot-features-developing-web-applications)

### Guides
The following guides illustrate how to use some features concretely:

* [Building a RESTful Web Service](https://spring.io/guides/gs/rest-service/)
* [Serving Web Content with Spring MVC](https://spring.io/guides/gs/serving-web-content/)
* [Building REST services with Spring](https://spring.io/guides/tutorials/bookmarks/)

### Additional Links
These additional references should also help you:

* [Gradle Build Scans – insights for your project's build](https://scans.gradle.com#gradle)



