
### user.md

```markdown
# User Endpoints

The user section provides endpoints for managing user profiles, including updating usernames, emails, passwords, and avatars.

## Endpoints

- **Get User Info (user):** `GET /user`
  - Retrieve user information.

- **Update Username (user):** `PUT /user/username`
  - Update the username.

- **Update Email (user):** `PUT /user/email`
  - Update the email address.

- **Update Password (user):** `PUT /user/password`
  - Update the user password.

- **Update Avatar (user):** `PUT /user/avatar`
  - Update the user avatar.

## Request Example

```json
{
  "newUsername": "new_username"
}
