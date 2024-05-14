# FastAPI Testing Example

This project demonstrates a simple FastAPI application with integrated tests. The application provides basic CRUD operations on a mock database of items, and the tests validate the functionality of these endpoints.

## Overview

The application includes:
- A FastAPI app with CRUD operations.
- Tests written using `pytest` that cover each operation.
- Usage of `TestClient` from `fastapi.testclient` for API endpoint testing.

## Command to run the test files:

```bash
cd test
pytest
