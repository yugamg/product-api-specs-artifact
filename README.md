# Product API Specification

This package contains the OpenAPI specification for the Product Service.

## Installation

```bash
npm install product-api-spec
```

## Usage

The OpenAPI specification can be accessed at `node_modules/product-api-spec/product-api-spec/openapi.json`.

## API Endpoints

- `GET /products/` - Get all products

## Schema

The API uses the following schema for products:

```json
{
  "id": "integer",
  "name": "string",
  "price_in_cents": "integer"
}
```

## License

MIT 