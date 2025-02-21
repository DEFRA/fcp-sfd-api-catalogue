# FCP Single Front Door (SFD) API Catalogue

## About
This is the home of documentation covering the APIs / integrations available within the FCP Single Front Door (SFD) service.

We use the following specifications to document our APIs:

* [OpenAPI](https://swagger.io/specification/) - for Restful APIs
* [AsyncAPI](https://www.asyncapi.com/) - for event-driven integrations
* [GraphQL Introspection](https://graphql.org/learn/introspection/)

Integrations are tagged according to their availability:

* `internal` - Internal Defra use only
* `sfd` - Internal SFD use only

We also tag available integrations with information around versioning and deprecation:

* `latest` - This is the latest version of the integration
* `retiring` - This version is being retired. Steps should be taken to migrate to a newer version
* `deprecated` - This version is deprecated and should not be used
