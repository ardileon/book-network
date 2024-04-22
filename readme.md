# JWT | SPRING BOOT | Login

Disini kita akan buat aplikasi spring boot dengan security dari spring security dan jwt

## Langkah ke-1
buat workspace dengan dependecies sebagai berikut :
1. Spring Web
2. Spring Data JPA
3. Validation
4. Java Mail Sender
5. Spring Security
6. Thymeleaf
7. PostgreSQL Driver
8. Lombok
9. JWT (add manual)
10. OPEN API

## Langka ke-2
Config application.properties -> applciation.properties.yml
```bash
spring.application.name=book-network // didelete
```
### pom.xml
delete : 
```python
<dependency>
	<groupId>org.thymeleaf.extras</groupId>
	<artifactId>thymeleaf-extras-springsecurity6</artifactId>
</dependency>
```
add JWT manually dan openapi
```python
<dependency>
	<groupId>io.jsonwebtoken</groupId>
	<artifactId>jjwt-api</artifactId>
	<version>0.12.5</version>
</dependency>

<dependency>
	<groupId>io.jsonwebtoken</groupId>
	<artifactId>jjwt-impl</artifactId>
	<version>0.12.5</version>
</dependency>

<dependency>
	<groupId>io.jsonwebtoken</groupId>
	<artifactId>jjwt-jackson</artifactId>
	<version>0.12.5</version>
</dependency>

<dependency>
	<groupId>org.springdoc</groupId>
	<artifactId>springdoc-openapi-starter-webmvc-ui</artifactId>
	<version>2.5.0</version>
</dependency>

```