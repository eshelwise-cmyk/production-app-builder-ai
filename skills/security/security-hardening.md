# Security Hardening

Every application review should include:

- Rate limiting on public endpoints
- Input validation and sanitization
- Secure authentication
- Authorization checks
- Secret management
- Dependency auditing
- OWASP review

Never expose API keys client-side.
Use environment variables and rotate credentials.