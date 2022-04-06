# Read: Class 12-  CRUD (Create, Read, Update, Delete)

[Status Codes Based on REST Methods](https://www.moesif.com/blog/technical/api-design/Which-HTTP-Status-Code-To-Use-For-Every-CRUD-App/)

1. In your own words, describe what each group of status code represents:

* 100’s = Tells the user that part of their request is recieved (the header)
* 200’s = Tells the user that their request has been accepted.
* 300’s = Tells the user what is requested is no longer available at the location so they need to request from the new available location
* 400’s = Occurs when the request is invalid. i.e wrong URL being used
* 500’s = Occurs when there is a server error code.

2.What is a status code 202?

* Status code 202 means everything went well

3.What is a status code 308?

* Status code 308 (permanent redirect) -  the resource is availabe at a new URL so the user should use this URL

4.What code would you use if an update didn’t return data to a client?

* Status code 204

5.What code would you use if a resource used to exist but no longer does?

* Status code 410 

6.What is the ‘Forbidden’ status code?

* ***Forbidden status code*** occurs when the client doesn't have access to the resource 


[Video: Build A REST API With Node.js, Express, & MongoDB- Quick](https://www.youtube.com/channel/UCFbNIlppjAuEX4znoulh0Cw)

1.Why do we need to pull our MongoDB database string out of our server and put it into our .env?

* So when we deploy our application it is not connected to our local host

2.What is middleware?

* ***Middleware*** is code that runs when the server recieves a request and before it is passed to the routes

3.What does app.use(express.json()) do?

* Sets up the server to accept JSON

4.What does the /:id mean in a route?

* It means that it is a parameter and it means that we can access it by typing `req.params.id`

5.What is the difference between PUT and PATCH?

* ***PUT*** updates all the information all at once while ***PATCH*** updates based on only what the user passes us

6.How do you make a default value in a schema?

* eg. `default: Date.now`

7.What does a 500 error status code mean?

* Means the server has an error

8.What is the difference between a status 200 and a status 201?

* ***200*** means everything worked successfully but status of 201 tells us we've created something