# GraphQLAPITesting

GraphQL is a query lanquage that describes how to ask for data, and is generally used to load data from a server to a client.
With GraphQL, the user is able to make a single call to fetch the required information rather than to construct several REST requests to fetch the same.
Visit https://graphql.org/learn/ to know more about GraphQL.

## Benefits of using GraphQL over REST
* The number of endpoints will be reduced as compared to that in REST API. In GraphQL a single endpoint can be used to query any data from the server

* Client can ask for any specific data by modifying the the api request. Nothing more than the data asked by the client is returned by the server.

Visit https://www.howtographql.com/basics/1-graphql-is-the-better-rest/ to get more details on this.

## Understanding GitHub GraphQL API v4

GitHub has exposed both REST API and GraphQL API for all the users.Both can be used to ask the GitHub server for information like github user details,followers,respositories,commits and many others.

Using GitHUb GraphQL API, a single endpoint is used to query all the informations of a github user. The client needs to specify the data which he wants from the github server in a graphql query and only the requested data is returned by the server.

Documentation of GitHub GraphQL API can be found at https://developer.github.com/v4/ .
Sample video for testing GitHub GraphQL API in postman- https://www.youtube.com/watch?v=GLdcIXjkb7k .

## Getting Started

Step 1. Clone or download this repository.

Step 2 : Import the Postman collection file in Postman.

Step 3 : Import the Postman enviroment file in Postman.

Step 4 : Enter your API KEY in api_key environment variable.

Step 5 :Add the GitHub GraphQL schema in postman.

Step 6 :You can execute the api request through postman or using newman.

### Prerequisites

1.Postman tool

2.GitHub Account for acessing the github api

## Built With

* Postman [https://www.postman.com/downloads/] - Client tool for testing APIs.


## Author

* **Vasant Verma** -(https://github.com/vasantverma)




