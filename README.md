# API Endpoints

## POST Endpoint: Register a new user

To register a new user, use the following `curl` command:

```bash
curl -X POST http://localhost:3000/register \
-H "Content-Type: application/json" \
-d '{"name": "John Doe", "email": "john.doe@example.com", "password": "123456"}'
```

## GET Endpoint: Fetch all user

```bash
curl http://localhost:3000/users
```
