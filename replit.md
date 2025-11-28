# Timestamp Microservice

## Overview
This is a FreeCodeCamp Timestamp Microservice project built with Node.js and Express. It provides a simple API for converting dates to timestamps and vice versa.

## Project Information
- **Source**: FreeCodeCamp boilerplate project (GitHub import)
- **Framework**: Express.js
- **Purpose**: API microservice for timestamp conversion
- **Date Imported**: November 28, 2025

## Project Structure
```
/
├── public/
│   └── style.css          # Styling for the frontend
├── views/
│   └── index.html         # Main HTML page with API documentation
├── index.js               # Express server and API endpoints
├── package.json           # Node.js dependencies
└── sample.env             # Environment variable template
```

## Configuration
- **Port**: 5000 (configured for Replit environment)
- **Host**: 0.0.0.0 (required for Replit proxy)
- **Workflow**: "Express Server" runs `npm start`

## API Endpoints
- `GET /` - Serves the HTML documentation page
- `GET /api/hello` - Example API endpoint
- `GET /api/:date?` - Timestamp conversion endpoint (to be implemented)

## Recent Changes
- **2025-11-28**: Initial Replit setup
  - Modified index.js to bind to 0.0.0.0:5000 for Replit environment
  - Configured Express Server workflow
  - Installed dependencies (express, cors)

## Dependencies
- express: ^4.12.4
- cors: ^2.8.0

## Development
The server automatically runs on port 5000 when started. The Express Server workflow is configured to run `npm start`.

## Deployment
Configured for Replit Autoscale deployment (stateless web application).
