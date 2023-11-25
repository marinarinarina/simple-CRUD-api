# Simple CRUD Board API using Node.js, Express, and TypeScript

## Features

1. For simplicity, Store data in-memory and not in an external database.

2. For security, Limit API access by following the rules below:

- Anyone can read data.

- Only authenticated users with a admin role can create, update, or delete items. The admin role will bundle the necessary permissions to execute these write operations.

## Project Dependencies

- express: Fast, unopinionated, minimalist web framework for Node.js.

- dotenv: Zero-dependency module that loads environment variables from a .env file into process.env.

- cors: Express middleware to enable CORS with various options.

- helmet: Express middleware to secure your apps by setting various HTTP headers, which mitigate common attack vectors.
