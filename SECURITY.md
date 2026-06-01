# Security Policy

## Supported Versions

| Version | Supported |
|---------|-----------|
| 1.0     | Yes       |

## Reporting a Vulnerability

Please do not report security vulnerabilities through public GitHub issues.

Use GitHub's private vulnerability reporting for this repository if it is available. If private reporting is not available, contact the repository owner directly before publishing details.

When reporting a vulnerability, include:

- A clear description of the issue.
- Steps to reproduce the behavior.
- The affected page, file, route, or function.
- Any relevant screenshots, logs, or request details with secrets removed.

## Security Notes

- Do not commit `.env`, `.env.local`, service-role keys, production database dumps, or unsanitized migration data.
- Netlify environment variables should store `SUPABASE_URL` and `SUPABASE_ANON_KEY`.
- Supabase service-role keys must stay server-side only.
- The `supabase/`, `.netlify/`, and `issues/` folders are ignored by default.
- Browser runtime config is served through `netlify/functions/config.js`.

## Current Security Version

Security policy version: 1.0
