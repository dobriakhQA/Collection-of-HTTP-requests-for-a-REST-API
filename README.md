# Collection-of-HTTP-requests-for-a-REST-API

This repository contains a collection of HTTP requests that interact with a free REST API that supports GET, POST, PUT, and DELETE requests. The purpose of this collection is to demonstrate the usage of variables, environments, and assertions in Postman, a popular API testing tool.

# Getting started

To use this collection, you will need to have Postman installed on your computer. You can download Postman from their official website: https://www.postman.com/downloads/
Once you have Postman installed, you can import the collection by clicking on the "Import" button in the top-left corner of the Postman app and selecting the REST_API_requests.postman_collection.json file from this repository.

# Variables

This collection uses variables to store sensitive information such as authentication credentials. You can set the values of these variables in the "Variables" tab of the collection. 

# Environments

This collection uses environments to run the same requests but authorized with different users. You can create a new environment by clicking on the "Manage environments" button in the top-right corner of the Postman app and selecting "Add" to create a new environment. You can then set the values of the variables in the new environment to run the requests with different credentials.

# Assertions

This collection uses assertions to check the status code 200 and 4xx in two of the requests, and to parse a JSON response to check the value of a parameter, such as a comment text or a username. You can view the assertions in the "Tests" tab of each request.

# Resources

If you would like to use a different REST API that supports the same HTTP requests, you can find a list of free REST APIs on the following websites:
1.	https://reqres.in
2.	https://jsonplaceholder.typicode.com
3.	https://restful-api.dev
