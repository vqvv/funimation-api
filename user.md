# User Endpoints

The user section provides endpoints for managing user profiles, including updating usernames, emails, passwords, and avatars.

## Endpoints

- **Get User Info (user):** `GET https://prod-api-funimationnow.dadcdigital.com/api/user/`
  - Retrieve user information.

- **Update Username (user):** `POST https://prod-api-funimationnow.dadcdigital.com/api/source/user/userid/`
  - Update the username.

- **Update Email (user):** `PUT https://prod-api-funimationnow.dadcdigital.com/api/user/email/`
  - Update the email address.

- **Update Password (user):** `PUT https://prod-api-funimationnow.dadcdigital.com/api/user/password/`
  - Update the user password.

- **Update Avatar (user):** `PUT https://prod-api-funimationnow.dadcdigital.com/api/user/avatar/`
  - Update the user avatar.

## Request Example for Update Username

```json
{
  "displayName": "username"
}
```
