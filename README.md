# Django

Complete login registration backend system using Spring Boot.

[![YouTube Video](https://user-images.githubusercontent.com/40702606/104790682-d62ac880-578f-11eb-8353-aa68739ffe42.png)](https://www.youtube.com/watch?v=QwQuro7ekvc)

- [x] Spring Boot
- [x] Spring Security
- [x] Java Mail
- [x] Email verification with expiry
- [x] Spring Boot

## Diagram
![Screenshot 2021-01-13 at 23 38 08](https://user-images.githubusercontent.com/40702606/104789980-15581a00-578e-11eb-998d-30f2e6a9f461.png)

## Email verification link with expiry
![Screenshot 2021-01-13 at 23 37 33](https://user-images.githubusercontent.com/40702606/104789893-0c674880-578e-11eb-939a-2a1cd3a8dfd2.png)

## Example requests
### Postman
![Screenshot 2021-01-13 at 23 37 57](file:///C:/Users/faisa/OneDrive/%E2%80%8F%E2%80%8F%D8%A7%D9%84%D8%B5%D9%88%D8%B1%20-%20%D9%86%D8%B3%D8%AE%D8%A9/%D8%A7%D9%84%D8%B5%D9%88%D8%B1/%D9%84%D9%81%D8%A9%20%D9%83%D8%A7%D9%85%D9%8A%D8%B1%D8%A7/%D9%84%D9%82%D8%B7%D8%A7%D8%AA%20%D8%A7%D9%84%D8%B4%D8%A7%D8%B4%D8%A9/Screenshot%202023-11-03%20034613.png)

### CURL
```
curl --location --request POST 'localhost:8080/api/v1/registration' \
--header 'Content-Type: application/json' \
--data-raw '{
    "firstName": "Amigos",
    "lastName": "Code",
    "email": "hellow@amigoscode.com",
    "password": "password"
}'
```
