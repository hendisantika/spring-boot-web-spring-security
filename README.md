# Spring Boot Spring Security Thymeleaf

####Spring Security

####Extends WebSecurityConfigurerAdapter, and defined the security rules in the configure method.

_*For user “admin” :*_

    * Able to access /admin page
    * Unable to access /user page, redirect to 403 access denied page.

_*For user “user” :*_

    * able to access /user page
    * unable to access /admin page, redirect to 403 access denied page.


#### To Run this :
`mvn spring-boot:run`

Access `http://localhost:8080`