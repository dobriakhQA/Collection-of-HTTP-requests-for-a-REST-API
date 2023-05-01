# Getting started

To use this collection, you will need to have Postman installed on your computer. You can download Postman from their official website: https://www.postman.com/downloads/
Once you have Postman installed, you can import the collection by clicking on the "Import" button in the top-left corner of the Postman app and selecting the REST_API_requests.postman_collection.json file from this repository.

# BookStore API HTTP Request Collection

This collection contains a series of HTTP requests for a REST API called "BookStore API". The collection is organized into four folders, each corresponding to a specific HTTP method: GET, POST, PUT, and DELETE.

## Folders

### GET

The **GET** folder contains requests for retrieving information from the BookStore API. The requests in this folder include:

**GET Books API:** retrieves a list of all books in the BookStore

**GET Books ISBN:** retrieves information about specific book in the BookStore by it ISBN. The ISBN is verified by a configured check that returns a validated value. 

### POST

The **POST** folder contains requests for creating new resources in the BookStore API. The requests in this folder include:

**User's list add new book:** adds a new book to the user’s collection of books

**New User:** creates a new user account

### PUT

The **PUT** folder contains requests for updating existing resources in the BookStore API. The requests in this folder include:

**Change Book:** updates information about a specific user’s collection of books

### DELETE

The **DELETE** folder contains requests for deleting resources from the BookStore API. The requests in this folder include:

**Delete Book:** removes a specific book from the user’s collection of books

## Environments

The BookStore API collection uses the "BookStore" environment to run the same requests but authorized with two different users. You can create a new environment by clicking on the "Manage environments" button in the top-right corner of the Postman app and selecting "Add" to create a new environment. You can then set the values of the variables in the new environment to run the requests with different credentials.

## Variables

The collection includes the following variables:

bookURL: the URL for accessing the BookStore API

ID, login and password: ID, login and password credentials for two users

## Endpoints

Endpoints for each request can be found on the following URL:https://bookstore.toolsqa.com/

If you would like to use a different REST API that supports the same HTTP requests, you can find a list of free REST APIs on the following websites:
1.	https://reqres.in
2.	https://jsonplaceholder.typicode.com
3.	https://restful-api.dev
