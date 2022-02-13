# RESTful-JSON-API using Go

This basic REST-API principle establishes a one-to-one mapping between create, read, update, and delete (CRUD) operations and HTTP methods. According to this mapping:

- OPTIONS = Get information about the communication options for the request URI
- GET = Retrieve a event or data of a resource
- POST = Create a event or add data to the resourse.
- DELETE = Delete if you are requesting the server to delete the resource
- PATCH = Update partial content of a resource


For storing JSON data, a struct events of event is created

Commands/URLs:

 OPTIONS :
  ```
  curl -X VIEW /events/options
 ```

 GET :
 ```
  curl -X /events
 ```
     or
 ```
  curl -X GET /events
 ```
  
 POST :
 
 ```
  curl -H "Content-Type: application/json" -X POST /event -d '{"id":"_ID_","title":"_TITLE_","description":"_DESCRIPTION_"}'
 ```
 
 PATCH:
 
 ```
  curl -H "Content-Type: application/json" -X PATCH /event -d '{"id":"_ID_","title":"_TITLE_","description":"_DESCRIPTION_"}'
 ```
  
 DELETE:
 
 ```
  curl -X DELETE /events/id
 ```
  
