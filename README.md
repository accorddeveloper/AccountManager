# AccountManager
C# MVC ASP.Net EF OAuth2 Registration and Login example

This manager provide user registration over OAuth2 and access token.
1.For new user registration send json data 
                                    "{
                                        "userName": "Ismayil",
                                        "password": "123456",
                                        "confirmPassword": "123456"
                                      }"
  to http://exampleurl/api/account/register.
2. For autorize and get token send x-www-form-urlencoded data 
                                    grant_type = password
                                    username = Ismayil
                                    password  = 123456
  to http://exampleurl/token
after successfull login you get back access_token and expire time and token type (bearer)
Please change DB path on web.config after locate this project.

