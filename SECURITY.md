# Security Policy

## Credential & Secret Management

- Never commit `.env`, `.env.local`, `serviceAccountKey.json`, `*firebase-adminsdk*.json`, keystores (`.jks`), or API secret tokens to Git.
- Use `.env.example` templates for documenting configuration variables without secret values.
- If a credential or Personal Access Token is accidentally exposed, revoke/rotate it immediately in the corresponding provider console (GitHub, Stripe, Telnyx, Cloudinary, MongoDB Atlas, or Firebase).

## Reporting a Vulnerability

Please report security issues privately to the engineering maintainers rather than opening public issues.
