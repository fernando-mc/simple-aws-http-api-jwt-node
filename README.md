# AWS HTTP API with Authorizer - Node

This example demonstrates how you can use the new AWS HTTP API (Announced Dec. 2019) and the built in JSON Web Token Authorization it offers. In this case, I've shown how to do so assuming that you've already been working with a tool like Cognito, Auth0 or Okta and have an `issuerUrl` and `audience` to add into the code.

Depending on your implementation and the tool, the `audience` could be something like an Auth0 API ID or a Cognito App Client ID.

For more details you can review the blog post [here](https://serverless.com/blog/serverless-auth-with-aws-http-apis).
