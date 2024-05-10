# OpenAPI autoclient for C#

An automatic client generator written in Typescript.
Under development.

## What it does

Given a JSON file with an [OpenAPI 3.1.0 specification](https://swagger.io/specification/),
the project reads it and generates the appropriate code for interacting with the
API described by the file.

## What is different from other solutions

Here, I am implementing the project in a way that the generated code has a
proper architecture and best practices for designing a client, including
dependency injection, repository pattern, and separation of concerns. Other
solutions didn't generate a code with such architecture, which could deteriorate
the code legibility in an existing project.

## Other similar projects

- [openapi-generator](https://github.com/OpenAPITools/openapi-generator) from OpenAPITools
- [swagger-codegen](https://github.com/swagger-api/swagger-codegen) from swagger-api
