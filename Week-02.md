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

## What I learned
I learned how the TCP/IP model works in layers (Application,
Transport, Internet, Network Access), and used traceroute to
see the Internet layer in action: each hop is a router making
an independent routing decision based only on the IP address.

## Commands I used
tracert github.com

## One thing I found hard
Understanding why some hops show "*" (timeout) — it's often a
deliberate security choice by routers, not a network failure.

