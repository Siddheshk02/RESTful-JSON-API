# RESTful-JSON-API using Go

This basic REST-API principle establishes a one-to-one mapping between create, read, update, and delete (CRUD) operations and HTTP methods. According to this mapping:

- GET = Retrieve a event or data of a resource
- POST = Create a event or add data to the resourse.
- DELETE = Delete if you are requesting the server to delete the resource
- PATCH = Update partial content of a resource
- OPTIONS = Get information about the communication options for the request URI

Commands for
 GET :
 ```
  curl -X http://localhost:8080/events
 ```
 or
 ```
  curl -X GET http://localhost:8080/events
  ```
  
  POST :
  
