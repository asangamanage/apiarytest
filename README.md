# apiarytest

## How to convert API blueprint to swagger
https://github.com/kminami/apib2swagger

### Install
npm install -g apib2swagger

### Generate Apib to Swagger
apib2swagger -i apiary.apib swagger.json > apibtoswagger.json

## Swagger codegen code
https://github.com/swagger-api/swagger-codegen

See command line OPTIONS to change package name and provide a new template.

### Sample mustach template in Swagger codegen source
swagger-codegen/modules/swagger-codegen/src/main/resources/JavaJaxRS/api.mustache
