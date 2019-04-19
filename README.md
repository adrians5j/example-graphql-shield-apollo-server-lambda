# About
A simple example that shows how to connect `graphql-shield` with `apollo-server-lambda`, using `graphlq-middleware`.

- [graphql-shield](https://github.com/maticzav/graphql-shield)
- [apollo-server-lambda](https://github.com/apollographql/apollo-server/blob/master/docs/source/deployment/lambda.md)
- [graphql-middleware](https://github.com/prisma/graphql-middleware)

This example is also included in the official `graphql-shield` repo: https://github.com/maticzav/graphql-shield/tree/master/examples/with-apollo-server-lambda.

# Run
Just clone the repo, run `npm install` and then `npm start` to start the GraphQL server on `http://localhost:3000`.

Running the following query in your GraphQL client will result with an authorisation error:
```graphql
{
  hello
}
```
