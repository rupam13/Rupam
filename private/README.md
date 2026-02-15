# Private Workspace

This folder adds a lightweight login-gated area inside the same repository:

- `private/index.html` -> login page
- `private/app.html` -> private workspace

## Current credentials

- Username: `rupam13`
- Password: `ChangeMe@2026`

## Important

This is a **client-side** gate (not server-side security).  
For true privacy/security, use a separate private GitHub repo or backend auth.

## Change credentials

1. In `private/index.html`, update the `HASH` value.
2. Generate a new SHA-256 hash of `username|password`.
3. Replace the old hash with the new one.
