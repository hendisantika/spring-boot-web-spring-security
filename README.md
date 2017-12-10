# Spring Boot Spring Security Thymeleaf

#### Spring Security

#### Extends WebSecurityConfigurerAdapter, and defined the security rules in the configure method.

**For user “admin” :**

    * Able to access /admin page
    * Unable to access /user page, redirect to 403 access denied page.

**For user “user” :**

    * able to access /user page
    * unable to access /admin page, redirect to 403 access denied page.


#### To Run this :
`mvn spring-boot:run`

Access `http://localhost:8080`

Login Home

![Login Home](img/login.png "Login Home Page")

Login Admin Home

![Login Admin Home](img/admin.png "Login Admin Home Page")

Login as Admin Home

![Login as Admin Home](img/hello_admin.png "Login Admin Home Page")

Logout Admin Home

![Login Admin Home](img/loguot.png "Logout Admin Home Page")

Login User Home

![Login User Home](img/user.png "Login User Home Page")

Login as User Home

![Login as Admin Home](img/hello_user.png "Login Admin Home Page")

Logout Admin Home

![Login Admin Home](img/logout.png "Logout User Home Page")
Login Admin Home

![Login Admin Home](img/admin.png "Login Admin Home Page")

Login as Admin Home

![Login as Admin Home](img/hello_admin.png "Login Admin Home Page")

Access Deniud Home

![Access Home](img/denied.png "Access Home Page")