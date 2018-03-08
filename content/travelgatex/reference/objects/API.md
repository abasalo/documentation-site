{
  "title": "API",
  "description": "",
  "weight": 1,
  "fields": [
    {
      "typeString": "ID!",
      "name": "code",
      "url": "/travelgatex/reference/scalars/id",
      "description": "",
      "isDeprecated": "",
      "args": null
    },
    {
      "typeString": "[Error!]",
      "name": "error",
      "url": "/travelgatex/reference/objects/error",
      "description": "",
      "isDeprecated": "",
      "args": null
    },
    {
      "typeString": "APIData",
      "name": "apiData",
      "url": "/travelgatex/reference/objects/apidata",
      "description": "",
      "isDeprecated": "",
      "args": null
    },
    {
      "typeString": "DateTime!",
      "name": "createdAt",
      "url": "/travelgatex/reference/scalars/datetime",
      "description": "",
      "isDeprecated": "",
      "args": null
    },
    {
      "typeString": "DateTime!",
      "name": "updatedAt",
      "url": "/travelgatex/reference/scalars/datetime",
      "description": "",
      "isDeprecated": "",
      "args": null
    }
  ],
  "requireby": [
    {
      "name": "APIEdge",
      "description": "",
      "url": "/travelgatex/reference/objects/apiedge"
    }
  ],
  "enumValues": null,
  "operator": "type",
  "typename": "API"
}
An API is a set of functions and procedures that allow the creation of applications which access the features or data of an operating system, application, or other service.

## GraphQL Schema definition

{{% graphql-schema-type %}}

## Fields

{{% graphql-field %}}

## Require by

{{% graphql-require-by %}}