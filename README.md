# PortSwigger SSRF Labs

Write-ups and evidence from PortSwigger Web Security Academy's Server-Side Request Forgery (SSRF) track, completed as part of hands-on practice for contract web application penetration testing.

Each lab folder contains:
- A write-up (objective, methodology, payloads used, and outcome)
- Screenshots documenting the request/response flow in Burp Suite
- Notes on real-world applicability of the technique

## Labs

| # | Lab | Status | Key Technique |
|---|-----|--------|----------------|
| 01 | [Basic SSRF against the local server](lab-01-basic-ssrf-local-server/README.md) | ✅ Solved | Abusing a server-side URL-fetching parameter to reach internal-only endpoints |
| 02 | [Basic SSRF against the local server](lab-02-basic-ssrf-local-server/README.md) | ✅ Solved | Basic SSRF against another back-end system |
| 03 | TBD | ✅ Solved | |

## Tools Used

- Burp Suite Community Edition (Repeater)
- Kali Linux (VMware)
- Firefox

## Why This Repo Exists

These write-ups double as a reference for identifying and reporting SSRF during contract web application pentests — documenting not just "it worked" but the full discovery process a client report would need.
