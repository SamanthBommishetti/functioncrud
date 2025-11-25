# Products CRUD API (Azure Functions + Cosmos DB)

This project implements a simple CRUD API using Python Azure Functions and Cosmos DB.

## Endpoints
- POST /api/create
- GET /api/get
- GET /api/get/{id}
- PUT /api/update/{id}
- DELETE /api/delete/{id}

## Requirements
- Azure Functions Core Tools
- Python 3.14
- Cosmos DB (NoSQL)

## Run Locally
npm i -g azure-functions-core-tools@4 --unsafe-perm trueP
func azurite
func start
