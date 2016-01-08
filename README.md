# Welcome future Kyngo Server Developer!

This is a super fun and exciting<sup>*</sup> challenge for you. You have 4 hours to complete this from the time you start. Good luck!

This project is a swagger (https://github.com/swagger-api/swagger-node) based node.js application. It will be up to you to add RESTful endpoints as instructed below.

0. Fork [this project](https://github.com/kyngoadmin/kyngo-node-test.git)!

1. Ensure the application is running properly in your development environment by going to (http://127.0.0.1:10010/hello?name=Developer)

2. Remove the hello_kyngo end point.

3. Add an endpoint called "widget" that will manage Widget objects.
  * This endpoint will accept get, post, delete and put requests to (get, create, detele and update, respectively). 
  * Widget objects will be stored in a mongolab database (the URL will be emailed to you before you begin) and referenced locally in a Mongoose schema.
    * This schema will contain the following fields:

      1. id - Number
      2. name - String
      1. created_on - Date

4. Add a swagger schema containing the same schema as above that will be sent or received when calling the above REST methods
   
5. Make a pull request with your changes.

## Bonus points (if you have time):
  * Add an endpoint called "kyngofun" that accepts a POST request that contains a string and returns an array
  * Update the "kyngofun" endpoint with the following:
  * Using a natural language processor, tokenize the string and return an array of each word (ie: "How are you?" would return ["How", "are", "you?"])


<sub>*excitement not guaranteed.</sub> 