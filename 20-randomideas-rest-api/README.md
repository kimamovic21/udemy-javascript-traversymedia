# 20 - RandomIdeas REST API

This project builds a REST API for a RandomIdeas app with Express, MongoDB, Mongoose, and environment-based configuration.

## Files

- `server.js` creates the Express app, connects to MongoDB, adds body parsing middleware, registers the ideas routes, and starts the server.
- `config/db.js` connects Mongoose to the `MONGO_URI` environment variable.
- `models/Idea.js` defines the idea schema and Mongoose model.
- `routes/ideas.js` defines the REST endpoints for listing, reading, creating, updating, and deleting ideas.
- `package.json` contains the app scripts and dependencies.
- `package-lock.json` locks the installed dependency versions.

## What This Covers

- Creating an Express API server.
- Loading environment variables with `dotenv`.
- Connecting to MongoDB with Mongoose.
- Defining a Mongoose schema and model.
- Parsing JSON and URL-encoded request bodies.
- Creating route modules with `express.Router()`.
- Returning JSON responses.
- Handling CRUD routes for API resources.
- Using async/await with database calls.
- Returning basic error responses from route handlers.

## Running The Project

Install dependencies, add a `MONGO_URI` value in an environment file, then run the development server:

```bash
npm install
npm run dev
```

The server defaults to port `5000` unless a `PORT` environment variable is provided.

## API Routes

- `GET /` returns the welcome message.
- `GET /api/ideas` returns all ideas.
- `GET /api/ideas/:id` returns one idea by ID.
- `POST /api/ideas` creates a new idea.
- `PUT /api/ideas/:id` updates an idea.
- `DELETE /api/ideas/:id` deletes an idea.

## Things To Notice

The API depends on `process.env.MONGO_URI`, so the database connection will fail until that environment variable is available.
