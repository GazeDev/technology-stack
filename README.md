# Technology-Stack
A description of the preferred technology stack for Gaze Pgh applications.

## Identity and Access Management: Keycloak

http://keycloak.org

Keycloak is an open source project by RedHat for identity and access management. It supports public client authentication with JWT and single-sign-on.

## Backend REST APIs
### Server: NodeJS and ExpressJS
https://nodejs.org, https://expressjs.com/

Our preferred backend is nodejs with express, but the language and framework doesn't matter so much as long as it is a REST API with JSON.

### Database: PostgreSQL
https://www.postgresql.org/

An open source object-relational database that allows flexibility in storage, including JSON.

### API Spec: OpenAPI and Swagger
https://www.openapis.org/, https://swagger.io/
Whatever implementation you choose, it should use the OpenApi spec to document the api, and we prefer Swagger for the display. We have found that self documenting APIs in the code is best, as opposed to a separately and manually maintained api spec.
