# Web Security Pre-Diagnostic Checklist

## Transport Security
- HTTPS enforced
- Valid TLS certificate
- HTTP → HTTPS redirection
- HSTS enabled

## Security Headers
- Content-Security-Policy
- X-Frame-Options / frame-ancestors
- X-Content-Type-Options
- Referrer-Policy
- Permissions-Policy

## Cookies
- Secure flag
- HttpOnly flag
- SameSite attribute

## Browser Permissions
- Camera / microphone restricted
- Sensors disabled if unused
- Background sync disabled if unused
- Web app installation disabled if unused

## Public Exposure
- Admin panels visibility
- Technology stack disclosure
- Error messages verbosity

## Risk Classification
- Critical: immediate fix required
- Medium: hardening recommended
- Low: best practice improvement
