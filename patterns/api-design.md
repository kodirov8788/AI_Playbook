# Reference Pattern: API Architecture Design

## Standard Response Envelope
All API endpoints must return a consistent payload:
```json
{
  "success": true,
  "data": {},
  "error": null,
  "meta": {
    "timestamp": "2026-05-29T14:44:43Z"
  }
}
```
- **Error Codes:** Map exceptions to standard HTTP response codes:
  - `400 Bad Request` for validation failures.
  - `401 Unauthorized` for missing or invalid tokens.
  - `403 Forbidden` for missing roles/scopes.
  - `404 Not Found` for invalid database queries.
