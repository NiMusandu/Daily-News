# Daily News

This repository no longer stores sensitive environment variables. Configure the required variables through your deployment platform or a secure secrets manager instead of committing them to version control.

## Environment Variables

- `VITE_REFRESH_MINUTES` – refresh interval for the frontend.
- `RESEND_API_KEY` – API key used for email services. **Rotate any previously committed key and set the new value securely.**

Copy `.env.example` to `.env` and fill in the appropriate values for local development. The `.env` file is ignored by Git.
