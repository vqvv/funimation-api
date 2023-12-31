# Authentication Endpoints

The authentication section provides endpoints for user authentication, including login and registration.

## Endpoints

- **Login (auth):** `POST https://prod-api-funimationnow.dadcdigital.com/api/auth/login/`
  - Authenticate the user.

- **Register (auth):** `POST https://prod-api-funimationnow.dadcdigital.com/api/auth/register/`
  - Create a new user account.

## Request Example For Login

```json
    {
        'username': "email@mail.com",
        'password': "password123"
    }
```
## Request Example For Register

```json
    {
        'username': "email@mail.com",
        'password': "password123",
        'subscription_id': "337",
        'emailSub': "false"
    }
```
