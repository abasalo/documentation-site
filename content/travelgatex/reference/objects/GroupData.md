{
  "title": "GroupData",
  "description": "",
  "weight": 1,
  "fields": [
    {
      "typeString": "ID!",
      "name": "id",
      "url": "/travelgatex/reference/scalars/id",
      "description": "",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "ID!",
      "name": "code",
      "url": "/travelgatex/reference/scalars/id",
      "description": "",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "String",
      "name": "label",
      "url": "/travelgatex/reference/scalars/string",
      "description": "",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "GroupType!",
      "name": "type",
      "url": "/travelgatex/reference/enums/grouptype",
      "description": "",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "String",
      "name": "info",
      "url": "/travelgatex/reference/scalars/string",
      "description": "",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "Group",
      "name": "parent",
      "url": "/travelgatex/reference/objects/group",
      "description": "",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "GroupConnection",
      "name": "children",
      "url": "/travelgatex/reference/objects/groupconnection",
      "description": "Only responses children.(non-hierarchically)",
      "isDeprecated": false,
      "args": [
        {
          "typeString": "[ID!]",
          "name": "codes",
          "url": "/travelgatex/reference/scalars/id",
          "description": ""
        },
        {
          "typeString": "Int",
          "name": "first",
          "url": "/travelgatex/reference/scalars/int",
          "description": ""
        },
        {
          "typeString": "Int",
          "name": "last",
          "url": "/travelgatex/reference/scalars/int",
          "description": ""
        },
        {
          "typeString": "String",
          "name": "before",
          "url": "/travelgatex/reference/scalars/string",
          "description": ""
        },
        {
          "typeString": "String",
          "name": "after",
          "url": "/travelgatex/reference/scalars/string",
          "description": ""
        },
        {
          "typeString": "GroupType",
          "name": "type",
          "url": "/travelgatex/reference/enums/grouptype",
          "description": ""
        },
        {
          "typeString": "String",
          "name": "codeStartsWith",
          "url": "/travelgatex/reference/scalars/string",
          "description": ""
        }
      ]
    },
    {
      "typeString": "GroupConnection",
      "name": "descendents",
      "url": "/travelgatex/reference/objects/groupconnection",
      "description": "Response all descendents groups nodes in this group (nom-hierarchically)",
      "isDeprecated": false,
      "args": [
        {
          "typeString": "[ID!]",
          "name": "codes",
          "url": "/travelgatex/reference/scalars/id",
          "description": ""
        },
        {
          "typeString": "GroupType",
          "name": "type",
          "url": "/travelgatex/reference/enums/grouptype",
          "description": ""
        },
        {
          "typeString": "Int",
          "name": "first",
          "url": "/travelgatex/reference/scalars/int",
          "description": ""
        },
        {
          "typeString": "Int",
          "name": "last",
          "url": "/travelgatex/reference/scalars/int",
          "description": ""
        },
        {
          "typeString": "String",
          "name": "before",
          "url": "/travelgatex/reference/scalars/string",
          "description": ""
        },
        {
          "typeString": "String",
          "name": "after",
          "url": "/travelgatex/reference/scalars/string",
          "description": ""
        },
        {
          "typeString": "String",
          "name": "codeStartsWith",
          "url": "/travelgatex/reference/scalars/string",
          "description": ""
        }
      ]
    },
    {
      "typeString": "GroupConnection",
      "name": "parents",
      "url": "/travelgatex/reference/objects/groupconnection",
      "description": "Response all parents groups nodes for this group (nom-hierarchically)",
      "isDeprecated": false,
      "args": [
        {
          "typeString": "[ID!]",
          "name": "codes",
          "url": "/travelgatex/reference/scalars/id",
          "description": ""
        },
        {
          "typeString": "GroupType",
          "name": "type",
          "url": "/travelgatex/reference/enums/grouptype",
          "description": ""
        },
        {
          "typeString": "Int",
          "name": "first",
          "url": "/travelgatex/reference/scalars/int",
          "description": ""
        },
        {
          "typeString": "Int",
          "name": "last",
          "url": "/travelgatex/reference/scalars/int",
          "description": ""
        },
        {
          "typeString": "String",
          "name": "before",
          "url": "/travelgatex/reference/scalars/string",
          "description": ""
        },
        {
          "typeString": "String",
          "name": "after",
          "url": "/travelgatex/reference/scalars/string",
          "description": ""
        }
      ]
    },
    {
      "typeString": "Member",
      "name": "owner",
      "url": "/travelgatex/reference/objects/member",
      "description": "",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "Boolean!",
      "name": "isEditable",
      "url": "/travelgatex/reference/scalars/boolean",
      "description": "",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "Int",
      "name": "productId",
      "url": "/travelgatex/reference/scalars/int",
      "description": "",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "Int",
      "name": "resourceId",
      "url": "/travelgatex/reference/scalars/int",
      "description": "",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "MemberConnection",
      "name": "members",
      "url": "/travelgatex/reference/objects/memberconnection",
      "description": "Only responses members in this group",
      "isDeprecated": false,
      "args": [
        {
          "typeString": "[ID!]",
          "name": "codes",
          "url": "/travelgatex/reference/scalars/id",
          "description": ""
        },
        {
          "typeString": "MemberType",
          "name": "type",
          "url": "/travelgatex/reference/enums/membertype",
          "description": ""
        },
        {
          "typeString": "Int",
          "name": "first",
          "url": "/travelgatex/reference/scalars/int",
          "description": ""
        },
        {
          "typeString": "Int",
          "name": "last",
          "url": "/travelgatex/reference/scalars/int",
          "description": ""
        },
        {
          "typeString": "String",
          "name": "before",
          "url": "/travelgatex/reference/scalars/string",
          "description": ""
        },
        {
          "typeString": "String",
          "name": "after",
          "url": "/travelgatex/reference/scalars/string",
          "description": ""
        }
      ]
    },
    {
      "typeString": "APIConnection",
      "name": "apis",
      "url": "/travelgatex/reference/objects/apiconnection",
      "description": "APIs assigned to this group. Products have APIs.",
      "isDeprecated": false,
      "args": [
        {
          "typeString": "[ID!]",
          "name": "codes",
          "url": "/travelgatex/reference/scalars/id",
          "description": ""
        },
        {
          "typeString": "Int",
          "name": "first",
          "url": "/travelgatex/reference/scalars/int",
          "description": ""
        },
        {
          "typeString": "Int",
          "name": "last",
          "url": "/travelgatex/reference/scalars/int",
          "description": ""
        },
        {
          "typeString": "String",
          "name": "before",
          "url": "/travelgatex/reference/scalars/string",
          "description": ""
        },
        {
          "typeString": "String",
          "name": "after",
          "url": "/travelgatex/reference/scalars/string",
          "description": ""
        }
      ]
    },
    {
      "typeString": "ManagedGroupConnection",
      "name": "managedGroups",
      "url": "/travelgatex/reference/objects/managedgroupconnection",
      "description": "Responses all managed groups by this group.",
      "isDeprecated": false,
      "args": [
        {
          "typeString": "[ID!]",
          "name": "group",
          "url": "/travelgatex/reference/scalars/id",
          "description": ""
        },
        {
          "typeString": "[ID!]",
          "name": "api",
          "url": "/travelgatex/reference/scalars/id",
          "description": ""
        },
        {
          "typeString": "[ID!]",
          "name": "resource",
          "url": "/travelgatex/reference/scalars/id",
          "description": ""
        },
        {
          "typeString": "[ID!]",
          "name": "role",
          "url": "/travelgatex/reference/scalars/id",
          "description": ""
        },
        {
          "typeString": "[ID!]",
          "name": "codes",
          "url": "/travelgatex/reference/scalars/id",
          "description": ""
        },
        {
          "typeString": "Int",
          "name": "first",
          "url": "/travelgatex/reference/scalars/int",
          "description": ""
        },
        {
          "typeString": "Int",
          "name": "last",
          "url": "/travelgatex/reference/scalars/int",
          "description": ""
        },
        {
          "typeString": "String",
          "name": "before",
          "url": "/travelgatex/reference/scalars/string",
          "description": ""
        },
        {
          "typeString": "String",
          "name": "after",
          "url": "/travelgatex/reference/scalars/string",
          "description": ""
        }
      ]
    },
    {
      "typeString": "MemberConnection",
      "name": "allMembers",
      "url": "/travelgatex/reference/objects/memberconnection",
      "description": "Response all members in this group's childrens (hierarchically),",
      "isDeprecated": false,
      "args": [
        {
          "typeString": "[ID!]",
          "name": "codes",
          "url": "/travelgatex/reference/scalars/id",
          "description": ""
        },
        {
          "typeString": "MemberType",
          "name": "type",
          "url": "/travelgatex/reference/enums/membertype",
          "description": ""
        },
        {
          "typeString": "Int",
          "name": "first",
          "url": "/travelgatex/reference/scalars/int",
          "description": ""
        },
        {
          "typeString": "Int",
          "name": "last",
          "url": "/travelgatex/reference/scalars/int",
          "description": ""
        },
        {
          "typeString": "String",
          "name": "before",
          "url": "/travelgatex/reference/scalars/string",
          "description": ""
        },
        {
          "typeString": "String",
          "name": "after",
          "url": "/travelgatex/reference/scalars/string",
          "description": ""
        }
      ]
    },
    {
      "typeString": "AccessConnection",
      "name": "accesses",
      "url": "/travelgatex/reference/objects/accessconnection",
      "description": "Access resources in a group",
      "isDeprecated": false,
      "args": [
        {
          "typeString": "[ID!]",
          "name": "codes",
          "url": "/travelgatex/reference/scalars/id",
          "description": ""
        },
        {
          "typeString": "Int",
          "name": "first",
          "url": "/travelgatex/reference/scalars/int",
          "description": ""
        },
        {
          "typeString": "Int",
          "name": "last",
          "url": "/travelgatex/reference/scalars/int",
          "description": ""
        },
        {
          "typeString": "String",
          "name": "before",
          "url": "/travelgatex/reference/scalars/string",
          "description": ""
        },
        {
          "typeString": "String",
          "name": "after",
          "url": "/travelgatex/reference/scalars/string",
          "description": ""
        }
      ]
    },
    {
      "typeString": "SupplierConnection",
      "name": "suppliers",
      "url": "/travelgatex/reference/objects/supplierconnection",
      "description": "Supplier resources in a group",
      "isDeprecated": false,
      "args": [
        {
          "typeString": "[ID!]",
          "name": "codes",
          "url": "/travelgatex/reference/scalars/id",
          "description": ""
        },
        {
          "typeString": "[ID!]",
          "name": "accessID",
          "url": "/travelgatex/reference/scalars/id",
          "description": ""
        },
        {
          "typeString": "Int",
          "name": "first",
          "url": "/travelgatex/reference/scalars/int",
          "description": ""
        },
        {
          "typeString": "Int",
          "name": "last",
          "url": "/travelgatex/reference/scalars/int",
          "description": ""
        },
        {
          "typeString": "String",
          "name": "before",
          "url": "/travelgatex/reference/scalars/string",
          "description": ""
        },
        {
          "typeString": "String",
          "name": "after",
          "url": "/travelgatex/reference/scalars/string",
          "description": ""
        }
      ]
    },
    {
      "typeString": "ClientConnection",
      "name": "clients",
      "url": "/travelgatex/reference/objects/clientconnection",
      "description": "Clients resources in a group",
      "isDeprecated": false,
      "args": [
        {
          "typeString": "[ID!]",
          "name": "codes",
          "url": "/travelgatex/reference/scalars/id",
          "description": ""
        },
        {
          "typeString": "[ID!]",
          "name": "name",
          "url": "/travelgatex/reference/scalars/id",
          "description": ""
        },
        {
          "typeString": "Boolean",
          "name": "isActive",
          "url": "/travelgatex/reference/scalars/boolean",
          "description": ""
        },
        {
          "typeString": "Int",
          "name": "first",
          "url": "/travelgatex/reference/scalars/int",
          "description": ""
        },
        {
          "typeString": "Int",
          "name": "last",
          "url": "/travelgatex/reference/scalars/int",
          "description": ""
        },
        {
          "typeString": "String",
          "name": "before",
          "url": "/travelgatex/reference/scalars/string",
          "description": ""
        },
        {
          "typeString": "String",
          "name": "after",
          "url": "/travelgatex/reference/scalars/string",
          "description": ""
        }
      ]
    },
    {
      "typeString": "RoleConnection",
      "name": "roles",
      "url": "/travelgatex/reference/objects/roleconnection",
      "description": "You can grant roles to members, which define the roles catalog for a group.",
      "isDeprecated": false,
      "args": [
        {
          "typeString": "[ID!]",
          "name": "codes",
          "url": "/travelgatex/reference/scalars/id",
          "description": ""
        },
        {
          "typeString": "RoleType",
          "name": "type",
          "url": "/travelgatex/reference/enums/roletype",
          "description": ""
        },
        {
          "typeString": "Int",
          "name": "first",
          "url": "/travelgatex/reference/scalars/int",
          "description": ""
        },
        {
          "typeString": "Int",
          "name": "last",
          "url": "/travelgatex/reference/scalars/int",
          "description": ""
        },
        {
          "typeString": "String",
          "name": "before",
          "url": "/travelgatex/reference/scalars/string",
          "description": ""
        },
        {
          "typeString": "String",
          "name": "after",
          "url": "/travelgatex/reference/scalars/string",
          "description": ""
        }
      ]
    }
  ],
  "requireby": [
    {
      "name": "Group",
      "description": "Groups are organized hierarchically.",
      "url": "/travelgatex/reference/objects/group"
    }
  ],
  "enumValues": null,
  "operator": "type",
  "typename": "GroupData",
  "hideGithubLink": true
}
## GraphQL schema definition

{{% graphql-schema-type %}}

## Fields

{{% graphql-field %}}

## Required by

{{% graphql-require-by %}}
