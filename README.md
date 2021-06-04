# graphql-demo 

This is a playground project to learn about the advantages and disadvantages of using GraphQL.
## Overview
GraphQL is a query language for APIs and a runtime for fulfilling those queires with our existing data. GraphQL provides a complete and understandable description of the data in APIs. gives clients the power to ask for exactly what they need and nothing more, makes it easier to evolve APIs over time.

## Problem solved

- Minimize data fetching
  Over-fecthing is a problem in APIs. Basic APIs always return a fixed strcuture of data. we should fetch the data we need. Using GraphQL we can minimize data fetching and improve the performance of our API.
  
  ![image](https://user-images.githubusercontent.com/24758636/120868173-50b38380-c58b-11eb-82d3-80be5f34e1ea.png)

- Minimize Application endpoint
  For particular resource, there usually are GET, POST, DELETE, PUT reqeust methods to query data. There are usually a lot of endpoints for a service. It is hard to query/control/maintain all these endpoints. This biggest problem we can solve using GraphQL. GraphQL has only one endpoint and makes the whole server a single custom endpoint that can reply to all data questions.


- Optimize API Versioning
  One of the biggest problem in general REST APIs is version controlling. For different reasons, sometimes we need to change backend APIs. To keep front-end working. we need to vertioning in our REST API. In GraphQL there's no need for it since you are fetching your APIs by adding or removing types.

## Problem brought
...

## To run the app

`npm install`

`node app.js`
