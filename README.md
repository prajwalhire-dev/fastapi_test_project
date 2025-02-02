# fastapi_test_project
A small test project demonstrating FastAPI functionality including GET, POST, PUT, DELETE methods with path and query parameters.

## Setup

1. Create virtual environment

python3 -m venv fastAPI_project


## How to run
source fastAPI_project/bin/activate

### Install required packages
`pip install fastapi uvicorn`

## Running the Application
Start the server with the following command:
`uvicorn myapi:app --reload`

The API will be available at http://127.0.0.1:8000


## API Endpoints
### The myapi.py file includes examples of:

1. GET endpoint
2. Path parameter operations
3. Query parameter operations
4. Combined path and query parameters
5. POST endpoint
6. PUT endpoint
7. DELETE endpoint

## Documentation
Once the server is running, you can access:

1. Interactive API documentation: http://127.0.0.1:8000/docs
2. Alternative API documentation: http://127.0.0.1:8000/redoc