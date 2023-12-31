# User Endpoints

The user section provides endpoints for managing user profiles, including updating usernames, emails, passwords, and avatars.

## Endpoints

- **Get User Info (user):** `GET https://prod-api-funimationnow.dadcdigital.com/api/user/YOURUSERID/`
  - Retrieve user information.

- **Update Username (user):** `POST https://prod-api-funimationnow.dadcdigital.com/api/source/user/YOURUSERID/`
  - Update the username.

- **Update Email (user):** `POST https://prod-api-funimationnow.dadcdigital.com/api/source/user/YOURUSERID/`
  - Update the email address.

- **Update Password (user):** `POST https://prod-api-funimationnow.dadcdigital.com/api/source/user/credentials/YOURUSERID/`
  - Update the user password.

- **Update Avatar (user):** `POST https://prod-api-funimationnow.dadcdigital.com/api/avatar/`
  - Update the user avatar.

## Request Example for Update Username

```json
{
  "displayName": "username"
}
```
## Request Example for Update Email

```json
{
  "email": "email@mail.com"
}
```
## Request Example for Update Password

```json
{
  "old_password": "password",
  "new_password": "Password",
  "email": "email@mail.com"
}
```
