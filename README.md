# Challenge
Your challenge is to build an API that tracks the number of accesses to website and allows a user to create an account. To count the accesses, you should use the API https://countapi.xyz, and to create the account, you can use any database and libraries of your choice. However, we want you to explain your choices and how they work (in detail, preferably).

## Tasks
* Create a route to increment the number of accesses:
  * POST /access
* Create a route to check the number of accesses:
  * GET /access
* Create a route to create a user:
  * POST /users
* Create a route to view user information:
  * GET /users/{id}

## Bonus
* Host the challenge on a server:
  * [URL]()
* Write tests for the code (unit, integration, and e2e):
  * [Tests](src/domain/use-cases)
* Documentation (open-api, flowcharts, etc.):
  * [Docs](docs)

## Instructions
We follow clean code principles and would like to see that reflected in your implementation:
https://github.com/ryanmcdermott/clean-code-javascript
We want a production-ready delivery, so think about building a resilient and secure system
Any solution will be accepted and evaluated equally as we want to understand your knowledge. However, it would be interesting to use the same architecture we use: Serverless Architecture (API Gateway + Lambda + DynamoDB);
For infrastructure, you may use Serverless Framework or Terraform