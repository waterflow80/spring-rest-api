# spring-rest-api
A simple Hello World REST API using Sring Boot framework.

## Languages and Tools
- Java 17
- Maven
- Spring Web

## Description
- The project contains a greeting service that, given a certain URL, returns back a greeting message in a JSON format.
- Example: 
  Server: localhost. Port: 8082. Default-end-point: '/api'.
  - URL: localhost:8082/api/greeting  ==> 
  {
    "id": 4,
    "content": "Hello, World!"
  }
  - URL: localhost:8082/api/greeting?name=Maria => 
   {
    "id": 4,
    "content": "Hello, Maria!"
  }
  
## Demo

![test_api](https://user-images.githubusercontent.com/82417779/221843962-9cb67b9e-9e79-4dcc-bb17-42c6f91c0143.gif)
