StudySpark Secure Prototype

Files:
- index.html
- app.js

Security approach:
- No accounts or payment handling yet.
- No third-party JavaScript.
- Content Security Policy included in the page.
- Referrer-Policy and X-Content-Type-Options included.
- User-provided values are rendered with textContent, not innerHTML.
- Input lengths/ranges are validated.
- Calculator data is processed locally and is not transmitted.
- Production hosting should also send equivalent security headers over HTTPS.

Important:
This is a secure-minded prototype, not a security guarantee. Before adding accounts,
payments, uploads, or sensitive user data, add server-side validation, authentication,
secure sessions/cookies, CSRF protection, rate limiting, access controls, logging,
backups, dependency scanning, and a security review.
