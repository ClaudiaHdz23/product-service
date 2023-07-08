# Product Service

Nodejs version: 18.x

## The purpose

The repository was created in order to add to AWS API Gateway and AWS Lambda with the help of serverless.

## Deploying

Prerequisites: NodeJS v18.x and higher

Follow the steps:

- git clone
- sls deploy

## Result Links
  - Server url: https://2ws8krsku3.execute-api.us-east-1.amazonaws.com/dev/
  - Frontend integration: https://d452lnzqkf712.cloudfront.net/
    
    ### Apis
    - GetProductList: https://v9j0h4dfhh.execute-api.us-east-1.amazonaws.com/dev/products
    - GetProductsById: https://v9j0h4dfhh.execute-api.us-east-1.amazonaws.com/dev/products/{productId}
    - CreateProduct: https://v9j0h4dfhh.execute-api.us-east-1.amazonaws.com/dev/products
    - ImportProduct: https://5pha0drcx9.execute-api.us-east-1.amazonaws.com/import

You can find the documentation of the apis in the attached swagger in this repository.
