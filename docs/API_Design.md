# API Design

## Overview
REST-based API for synchronizing product data.

## Endpoints
- POST /products
- PUT /products/{id}
- GET /products/{id}

## Versioning
- v1 via URL versioning
- Backward compatibility guaranteed within major versions

## Error Handling
- Standardized error codes
- Retry-safe operations
