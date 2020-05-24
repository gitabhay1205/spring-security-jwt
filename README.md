# spring-security-jwt
This is the sample project for spring-security for generating and validating jwt tokens.

First make a Post request to http://localhost:8080/authenticate
with body 
{
	"username":"foo",
	"password":"foo"
}

This will give you jwt token.

After that hit http://localhost:8080/home, with Authorization header and Beared Token value from above request
