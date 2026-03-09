# graphql-demo

graphql-demo
use this endpoint to access graphql = http://localhost:8080/graphql
Youtube = https://youtu.be/eD-1KTK7fGc

access graphql from browser = http://localhost:8080/graphiql?path=/graphiql

The Core Problem It Solves
Traditional REST APIs often suffer from:
1. Over-fetching — getting more data than you need
2. Under-fetching — needing multiple requests to get all the data you need
GraphQL solves both in a single, flexible query.

Key Reasons It's Used
1. Fetch exactly what you need
Clients specify precisely which fields they want, nothing more. A mobile app can request a lighter payload than a desktop app from the same endpoint.

2. Single endpoint
Instead of /users, /users/posts, /users/posts/comments — everything goes through one endpoint (/graphql), and the query shape determines the response shape.

3. Nested/related data in one request
You can fetch a user, their posts, and each post's comments all in a single round-trip — no waterfall of API calls.

4. Strongly typed schema
GraphQL uses a schema to define all available data and operations. This acts as a contract between frontend and backend, enables auto-documentation, and catches errors early.

5. Great for complex, interconnected data
It excels when data has lots of relationships (social graphs, e-commerce, dashboards) — which is why Facebook built it.

6. Easier frontend development
Frontend teams can iterate on data requirements without asking backend to create new endpoints. They're more independent.