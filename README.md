# My-API-Gateway
April 26th Programming Activity

Setup

1. Copy project into XAMPP's htdocs folder.

2. Start Apache server.

3. Access API at http://localhost/my_api_gateway/.

API Keys

key123 (UserA)

key456 (UserB)

Endpoints

GET /api/users

GET /api/products

Headers required:

X-API-Key: [your key]

Features

API Key Authentication

Rate Limiting (10 requests/min)

Centralized Logging

API Documentation (docs.html)

Testing

Use Postman to:

Send valid and invalid API Keys

Rapid requests to test rate limiting

View logs at logs/gateway.log

Bonus

(No bonus tasks implemented.)
