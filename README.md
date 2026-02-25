# Product Store Backend API

## Overview
This project is a backend REST API for a product store, built with Node.js, Express.js, and MongoDB. It provides endpoints for managing products and follows a modular, scalable project structure.

The API has been tested using Postman to send JSON payloads and validate server responses.

## Features
- Connects to MongoDB using Mongoose
- Uses environment variables for sensitive configuration
- RESTful CRUD API for products
- Modular folder structure (controllers, models, routes, config)
- Tested with Postman for request/response validation
- Sensitive files like `.env` are protected by `.gitignore`

## Project Structure
```
backend/
  server.js           # Main server file
  config/
    db.js             # Database connection setup
  controllers/
    product.controller.js  # Product logic
  models/
    product.model.js       # Product schema
  routes/
    product.route.js       # Product API routes
frontend/                  # Placeholder for frontend
.env                       # Environment variables (not shared)
.gitignore                 # Prevents sensitive files from being committed
```

## API Endpoints
- `GET /api/products` — List all products
- `POST /api/products` — Create a new product
- `PUT /api/products/:id` — Update a product
- `DELETE /api/products/:id` — Delete a product

## Testing with Postman
All API endpoints were tested using Postman by sending JSON payloads and validating:
- Status codes
- Returned objects
- Error handling
- Database persistence

Example operations tested:
- Creating products
- Fetching all products
- Updating products
- Deleting products

A Postman collection is included in the postman/ folder for quick import and testing.

## Frontend

The frontend is built using React, Javascript, Chakra UI, and Vite.

## Future Steps
- Continue expanding the project, both frontend and backend
- Add authentication and authorization
- Expand other product features
