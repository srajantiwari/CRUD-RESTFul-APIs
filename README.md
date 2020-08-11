CRUD RESTFul APIs using Spring Boot, JPA and H2 database

Spring boot comes with TomCat, which makes us perform CRUD operations on localhost:8080

Operations available:
1. GET - api/v1/employees - returns list of all employees.
2. GET - api/v1/employees/{id} - returns record emplyee with particular id
3. POST - api/v1/employees/ - stores employee record post validation using Javax
4. PUT - api/v1/employees/{id} - updates employee record with particular id
5. DELETE - api/v1/employees/{id} - deletes record if found else return custom exception ResorceNotFoundException