{
  "title": "MemberConnection",
  "description": "",
  "weight": 1,
  "fields": [
    {
      "typeString": "[MemberEdge]",
      "name": "edges",
      "url": "/paymentx/reference/objects/memberedge",
      "description": "",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "PageInfo!",
      "name": "pageInfo",
      "url": "/paymentx/reference/objects/pageinfo",
      "description": "",
      "isDeprecated": false,
      "args": null
    }
  ],
  "requireby": [
    {
      "name": "GroupData",
      "description": "",
      "url": "/paymentx/reference/objects/groupdata"
    },
    {
      "name": "GroupCommonData",
      "description": "",
      "url": "/paymentx/reference/interfaces/groupcommondata"
    },
    {
      "name": "OrganizationData",
      "description": "",
      "url": "/paymentx/reference/objects/organizationdata"
    }
  ],
  "enumValues": null,
  "operator": "type",
  "typename": "MemberConnection",
  "hideGithubLink": true
}
## GraphQL schema definition

{{% graphql-schema-type %}}

## Fields

{{% graphql-field %}}

## Required by

{{% graphql-require-by %}}
