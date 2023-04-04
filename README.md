# Testing Api Gateway with ASP.NET Core6

Exercise on the implementation of Ocelot in the API Gateway concept incorporating JWT Token for the authorization of the Posts microservice.

```text
 docker build -t api-gateway:v1 -f .\src\ApiGateway\Dockerfile .
 docker build -t user-service:v1 -f .\src\UserService\Dockerfile .
 docker build -t post-service:v1 -f .\src\PostService\Dockerfile .
 docker build -t auth-service:v1 -f .\src\AuthService\Dockerfile .
```

## Technologies

* [ASP.NET Core 6](https://learn.microsoft.com/es-es/aspnet/core/release-notes/aspnetcore-6.0?view=aspnetcore-7.0)
* [Ocelot](https://github.com/ThreeMammals/Ocelot)
* [JWT Token](https://www.c-sharpcorner.com/article/how-to-implement-jwt-authentication-in-web-api-using-net-6-0-asp-net-core/)
