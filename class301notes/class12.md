# REST API ReadMe

### Reading: Status Codes Based On REST Methods

[Status Codes Based On REST Methods](https://www.moesif.com/blog/technical/api-design/Which-HTTP-Status-Code-To-Use-For-Every-CRUD-App/)

#### 100’s =

The 100-series status codes indicate provisional responses, informing the client that the server has received the request and is continuing to process it.

#### 200’s =

Status codes in the 200-series signify success. They indicate that the client's request was received, understood, and accepted.

#### 300’s =

Codes in the 300-series represent redirection. They indicate that further action needs to be taken to complete the request.

#### 400’s =

Status codes starting with 4 signify client errors. They indicate that the client seems to have made an error in the request.

#### 500’s =

The 500-series codes denote server errors. They indicate that the server failed to fulfill a valid request.

#### What is a status code 202?

Status code 202 means that the request has been accepted for processing but hasn't been completed. The server might continue processing the request in the background.

#### What is a status code 308?

Status code 308 indicates that the resource requested by the client has permanently moved to another location.

#### What code would you use if an update didn’t return data to a client?

In this case, a status code of 204 (No Content) would be appropriate.

#### What code would you use if a resource used to exist but no longer does?

A status code of 410 (Gone) would be used to indicate that the requested resource is no longer available.

#### What is the ‘Forbidden’ status code?

The 'Forbidden' status code (403) indicates that the server understood the request, but it refuses to authorize it.

### Videos: Build A REST API With Node.js, Express, & MongoDB - Quick - First 20 minutes

[Build A REST API With Node.js, Express, & MongoDB - Quick](https://www.youtube.com/channel/UCFbNIlppjAuEX4znoulh0Cw)

#### Why do we need to pull our MongoDB database string out of our server and put it into our .env?

Storing the MongoDB database string in a .env file enhances security by keeping sensitive information separate and preventing accidental exposure.

#### What is middleware?

Middleware functions have access to the request object, response object, and the next middleware function in the application's request-response cycle. They can perform tasks, modify request or response objects, and end the request-response cycle.

#### What does app.use(express.json()) do?

`app.use(express.json())` is middleware in Express that parses incoming requests with JSON payloads and makes the data available in the `req.body` object.

#### What does the /:id mean in a route?

The `/` followed by `:id` in a route represents a route parameter, allowing dynamic handling of different resource identifiers.

#### What is the difference between PUT and PATCH?

PUT is used to update or create a resource, while PATCH is used to partially update a resource. PUT typically requires sending the entire updated resource, whereas PATCH only requires the changes.

#### How do you make a default value in a schema?

A default value in a schema can be set by providing a default property in the schema definition.

#### What does a 500 error status code mean?

A status code of 500 indicates a server error, implying that the server encountered an unexpected condition that prevented it from fulfilling the request.

#### What is the difference between a status 200 and a status 201?

A status code of 200 means the request was successful, while a status code of 201 indicates that the request has been fulfilled and resulted in the creation of a new resource.

## Why This Matters

Understanding status codes and building a REST API with Node.js, Express, and MongoDB is crucial for developing robust and secure web applications. These concepts form the foundation of effective communication between clients and servers.

## Things I Want to Know More About

- Further exploration of advanced middleware usage.
- Deeper understanding of handling errors in a REST API.
- Investigating best practices for securing MongoDB connections in a production environment.

*
