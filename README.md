# Product Store Backend API

## Overview
This project is a backend API for a product store, built with Node.js, Express.js, and MongoDB. It provides RESTful endpoints for managing products.

## Features
- Connects to MongoDB using Mongoose
- Uses environment variables for sensitive configuration
- REST API endpoints for CRUD operations on products
- Organized project structure (controllers, models, routes, config)
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

## Future Steps
- Implement frontend in the `frontend/` folder
- Add authentication and authorization
- Expand product features