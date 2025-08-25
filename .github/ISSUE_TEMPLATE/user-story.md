---
name: User story
about: this template defines a user story
title: ''
labels: ''
assignees: ''

---

.
Question 1
Which of the following statements best describes how an entity and its attributes are represented in a relational database?


An entity becomes a table, and attributes become columns



An entity becomes a key, and attributes become values



An entity becomes a column, and attributes become rows



An entity becomes a schema, and attributes become foreign keys


1 point
2.
Question 2
What is the key difference between MongoDB and traditional relational databases?


Traditional databases offer higher scalability and flexibility than MongoDB



MongoDB stores data in rigid tables with fixed schemas



MongoDB does not support indexing or data aggregation



MongoDB uses documents stored in BSON format, offering flexible, semi-structured data


1 point
3.
Question 3
Which of the following best describes the role of a Database Management System (DBMS)?


It is a system that connects different databases using the internet



It only stores the data in a tabular format



It allows users to create, store, retrieve, and modify data within a database using queries



It acts as a graphical tool to visualize data in picture formats only


1 point
4.
Question 4
Which of the following is a primary benefit of using NoSQL databases?


Limited data structure options



Strict relational schema enforcement



Horizontal scalability



Requires expensive mainframes to operate


1 point
5.
Question 5
Which of the following statements is TRUE about using MongoDB with Node.js?


You do not need to install any drivers or libraries to connect Node.js with MongoDB 



Redis is a document-oriented NoSQL database designed for offline mobile access



It is possible to connect Node.js to MongoDB using the mongoClient.connect() method from the official MongoDB driver



Mongoose is a database that replaces MongoDB when used with Node.js


1 point
6.
Question 6
Which of the following is a feature of MongoDB that makes it different from most SQL databases?


Collections in MongoDB are the same as SQL indexes



It requires a fixed schema structure before data insertion.



Related data can be embedded within a single document



Each document must share the same field types and values


1 point
7.
Question 7
Which of the following is a widely adopted method for implementing authentication in a Node.js application?


Attribute-Based Access Control (ABAC)



Role-Based Access Control (RBAC)



JSON Web Tokens (JWT) 



OAuth2 Provider used solely for session storage


1 point
8.
Question 8
Which of the following is a recommended security practice to mitigate session hijacking and Cross-Site Request Forgery (CSRF) attacks when handling user sessions in Node.js?


Disabling session expiration



Using encryption algorithms such as AES to secure session data 



Avoiding the use of middleware for session management



Storing session IDs in URL parameters


1 point
9.
Question 9
In an Express.js application, middleware plays an essential role in the request-response cycle. What is one of its primary purposes?


To replace routes with custom logic



To define the controller logic that fetches data from the database



To directly perform CRUD operations on MongoDB collections



To process, inspect, or modify requests before they reach the route handler


1 point
10.
Question 10
Which versioning approach in RESTful APIs keeps URLs clean but requires clients to modify request headers to specify the API version?


Query parameter versioning



Media type versioning



URL versioning



Header versioning 


1 point
11.
Question 11
Which HTTP method and endpoint are typically used to update a specific resource in a RESTful API?


GET /api/resource



PUT /api/resource/:id 



DELETE /api/resource/:id



POST /api/resource/:id


1 point
12.
Question 12
Which of the following is the best practice for handling JWTs in a Node.js and Express application?


Store JWTs in the frontend UI code for easy access



Store refresh tokens securely and use them to request new access tokens 



Set tokens to never expire to reduce login frequency



Use short, easy-to-remember secret keys for faster performance


1 point
13.
Question 13
Which of the following techniques is used to handle multiple types of errors in advanced error-handling middleware?


Propagating errors using throw, and handling them using custom error classes such as ValidationError and DatabaseError 



Using console.log statements for debugging errors



Using only the default error handler in Express



Ignoring errors in nested functions to avoid disruptions


1 point
14.
Question 14
Which Node.js pattern uses the error-first convention for handling asynchronous errors?


Callbacks 



Promises



Event emitters



Async/await


1 point
15.
Question 15
What is the main advantage of using libraries such as “Joi" or "Express-validator” for request validation in Node.js applications?


They automatically sanitize all user inputs



They handle authentication and authorization



They provide declarative and well-tested validation rules



They reduce the need for middleware functions


1 point
16.
Question 16
Which logging tool is a middleware for logging HTTP requests in Node.js?


Winston



Morgan



Debug



Node-inspector


1 point
17.
Question 17
What does the upload.single('file') function do in a Node.js Express route using Multer?


Validates user authentication before uploading



Uploads multiple files in a single request



Handles uploading one file per request under the 'file' field name



Streams the uploaded file directly to a database


1 point
18.
Question 18
Why is it important to use environment variables when deploying a Node.js application?


To store sensitive configuration values separately from the codebase



To track memory usage and response times during runtime



To simplify the process of containerizing the application with Docker



To log HTTP requests in the application


1 point
19.
Question 19
A developer is building a Node and Express application and wants to improve code structure, manage database interactions cleanly, and ensure security. Based on best practices, which set of actions would best support these goals?


Focus only on frontend design, as backend structure and security aren’t necessary for Node applications



Apply the MVC (Model-View-Controller) pattern for organization, use ORM (Object-Relational Mapping) libraries such as Mongoose or Sequelize, and implement input validation and authentication mechanisms



Build the app without separation of concerns, avoid third-party tools, and expose database credentials directly in the source code



Use a monolithic file structure, connect directly to the database with raw SQL, and rely solely on console logs for security


1 point
20.
Question 20
A development team is designing a Node.js application expected to serve millions of users globally. They want to ensure fast response times, prevent overloading any single server, and keep the service running even during partial failures. Based on best practices discussed in the video, which combination of strategies would best support their goal?


Apply sticky sessions using hard-coded IPs, skip failure detection to reduce complexity, and rely on browser-based caching for session recovery



Use round-robin DNS, log errors using console.log, and run a single server instance for simplicity



Configure Nginx as a reverse proxy with session persistence, deploy multiple Node instances with the cluster module, and use Redis for distributed session caching



Build the application using monolithic architecture, avoid using any load balancer, and rely on Node’s non-blocking I/O alone for performance


1 point
