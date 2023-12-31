# Authentication Endpoints

The authentication section provides endpoints for user authentication, including login and registration.

## Endpoints

- **Login (auth):** `POST /auth/login`
  - Authenticate the user.

- **Register (auth):** `POST /auth/register`
  - Create a new user account.

## Request Example

```json
{
  "username": "example_user",
  "email": "example@example.com",
  "password": "password123"
}
