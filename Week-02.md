## What I learned
This week I learned how HTTPS/TLS works: it both encrypts traffic
and verifies the server's identity via a certificate issued by a
trusted Certificate Authority (CA).

## Commands I used
curl -I https://github.com
# → checked response headers to confirm HTTPS was in use

## One thing I found hard
Understanding that encryption alone isn't enough — the certificate
is what prevents a man-in-the-middle attack by proving identity.
