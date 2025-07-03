# Task 3 — Application of GraphQL in React with Next.js

## Objective

Set up a Next.js project with TypeScript, ESLint, Tailwind CSS, and Apollo Client to start building a Rick and Morty app.

---

## Steps

1. Created a new Next.js project named `alx-rick-and-morty-app` inside the `alx-graphql-0x01` directory.
2. Installed dependencies:
   - `@apollo/client`
   - `graphql`
   - `@types/graphql`
3. Created a `graphql` directory with:
   - `apolloClient.ts`: Configured Apollo Client with the Rick and Morty GraphQL endpoint.
   - `queries.ts`: Defined a GraphQL query `GET_EPISODES` to fetch episodes with pagination and filtering.
4. Modified `_app.tsx` to wrap the application with `ApolloProvider` for GraphQL integration.
5. Run the development server with `npm run dev` and checked the app at [http://localhost:3000](http://localhost:3000).

---

## Files Structure

| File                    | Description                   |
| ----------------------- | ----------------------------- |
| graphql/apolloClient.ts | Apollo Client setup           |
| graphql/queries.ts      | GraphQL queries for episodes  |
| pages/\_app.tsx         | Wraps app with ApolloProvider |

---

## Usage

- Use `GET_EPISODES` query in your React components to fetch episode data.
- Apollo Client handles caching and state management.

---
