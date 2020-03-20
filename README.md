# Autenticacao-e-Autorizacao-via-Token
Curso Balta.io (https://www.youtube.com/watch?v=UZ2Qa4xosl0)

Para testar, basta abrir o Postman realizar as requisições:

- POST 
  https://localhost:5001/v1/account/login (passando o username e password pelo body)
  
- GET
  https://localhost:5001/v1/account/anonymous
  https://localhost:5001/v1/account/authenticated
  https://localhost:5001/v1/account/employee?Authorized
  https://localhost:5001/v1/account/manager
  
  (informando no HEADERS a key: Authorization e value: Bearer tokenGerado)
