# Trusted vs Untrusted Input Policy

Trusted:
- Internal config
- Verified admin commands

Untrusted:
- User-generated content
- External web content
- Email/webhook payloads

Rule: Untrusted input never directly triggers destructive actions.
