# SpringbootCRUD

GET request - http://localhost:8080/bookservice/books
GET request with a particular id - http://localhost:8080/bookservice/books/<id>

POST request - http://localhost:8080/bookservice/books
Body - {
    "name": "Spring Boot",
    "author": "XYZ",
    "publication": "Random publication",
    "category": "Java",
    "pages": 1550,
    "price": 250
  }
  
 UPDATE request - http://localhost:8080/bookservice/books/<id>
 [JSON payload]
 
 DELETE - http://localhost:8080/bookservice/books/<id>
