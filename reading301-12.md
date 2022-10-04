# Reading: Class 12 - CRUD

## Status Codes Based On REST Methods

1. In your own words, describe what each group of status code represents:

   100’s = Simply informational in nature
   200’s = These are success codes
   300’s = These indicate to the user that a redirection has occurred
   400’s = These are errors codes related to the client
   500’s = These are error codes related to the server

2. What is a status code 202?

   It tells the client that the request was valid and accepted.

3. What is a status code 308?

   This indicated to the client that the URL has been permanently redirected.

4. What code would you use if an update didn’t return data to a client?

   204

5. What code would you use if a resource used to exist but no longer does?

   410

6. What is the ‘Forbidden’ status code?

   403

## Building a REST API With Node.js, Express, & MongoDB

1. Why do we need to pull our MongoDB database string out of our server and put it into our .env?

   The .env file is use to keep the information more secure and for convenience.

2. What is middleware?

   Middleware sits between two systems to assist in the communication, such as translating or normalizing.

3. What does app.use(express.json()) do?

   It is a method that is used to parse the incoming requests with JSON payloads.

4. What does the /:id mean in a route?

   It is a dynamic route.

5. What is the difference between PUT and PATCH?

   Using PUT requires us to specify all attributes even if we want to change only one attribute. But if we use the PATCH method we can update only the fields we need and there is no need to mention all the fields. PATCH does not allow us to modify a value in an array, or remove an attribute or array entry.[^1]

6. How do you make a default value in a schema?

   A _default: '\<default value>'_ can be placed in the schema object to set a default for when the value is undefined.

7. What does a 500 error status code mean?

   It means that the server encountered an unexpected condition that prevented it from fulfilling the request.

8. What is the difference between a status 200 and a status 201?

   The 200 status code is by far the most common returned. It means, simply, that the request was received and understood and is being processed. A 201 status code indicates that a request was successful and as a result, a resource has been created.[^2]

## Things I want to know more about

---

[^1]: _What is the main difference between PATCH and PUT request?_, Retrieved on October 3, 2022, from [https://stackoverflow.com/questions/21660791/what-is-the-main-difference-between-patch-and-put-request](https://stackoverflow.com/questions/21660791/what-is-the-main-difference-between-patch-and-put-request)
[^2]: _HTTP Status Codes for Beginners_, Retrieved on October 3, 2022, from [https://aloneonahill.com/blog/http-status-codes#:~:text=Successful&text=The%20200%20status%20code%20is,understood%20and%20is%20being%20processed.&text=A%20201%20status%20code%20indicates,for%20example%20a%20new%20page).](https://aloneonahill.com/blog/http-status-codes#:~:text=Successful&text=The%20200%20status%20code%20is,understood%20and%20is%20being%20processed.&text=A%20201%20status%20code%20indicates,for%20example%20a%20new%20page).)
