# graphql-demo 

This is a playground project to learn about the advantages and disadvantages of using GraphQL.

## Problem solved

- Minimize data fetching
  Over-fecthing is a problem in REST APIs. Basic REST APIs always return a fixed strcuture of data. we should fetch the data we need. Using GraphQL we can minimize data fetching and improve the performance of our REST API.

- Minimize Application endpoint
  For particular resource, there usually are GET, POST, DELETE, PUT reqeust methods to query data. There are usually a lot of endpoints for a service. It is hard to query/control/maintain all these endpoints. This biggest problem we can solve using GraphQL. GraphQL has only one endpoint and makes the whole server a single custom endpoint that can reply to all data questions.


- Optimize API Versioning
  One of the biggest problem in general REST APIs is version controlling. For different reasons, sometimes we need to change backend APIs. To keep front-end working. we need to vertioning in our REST API. In GraphQL there's no need for it since you are fetching your APIs by adding or removing types.


## To run the app

`npm install`

`node app.js`
