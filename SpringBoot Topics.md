---
title: "SPRING BOOT TOPICS"
format: html
---
En java hay tres conceptos de aprender:
wrapper
collection
container

Aparte de ArrayList y Arrays hay LinkedList, Vector, Stacks, Optional.
Containers in Java can be clasified into:
  Response
  Non-Response
Mirar esto: https://github.com/pedroGEOGIScoding/pronunciationApp/blob/backend-spring-boot/backend/resources/Containrs/Containers-Spring.md

Las 5 principales dependencias para elegir en https://start.spring.io/ son:
1. Spring Boot DevTools
2. H2 database
3. Spring Data JPA
4. Spring Web
5. Lombok

La estructura de carpetas es muy estrcita:
1. Model. Aqui esta las clase de Java y cada clase de Java tiene su controller, service and repository
  2. Controller
  3. Service
  4. Repository



1. When running SpringBoot and getting access to the H2 database from SpringBoot app, the script of H2 has to be stopped in the terminal console, in other words with the session closed, otherwise SpringBoot will stop warning that the port is busy with another app ("Address already in use").

2. In the same and opposite way, for adding items manually in the H2 database, the SpringBoot app should be stopped, not running, otherwise when trying to connect through the browser the terminal console will show a message that the port is used by another app, in this case SpringBoot.

3. After adding items manually in the H2 database, the teminal (browser) session should be shut down to close down the localhost:8080 to free it to the SpringBoot app.

