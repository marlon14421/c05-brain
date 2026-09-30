---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-1385"
status: "Incomplete"
---
# CWE-1385: Missing Origin Validation in WebSockets

**Abstraction:** Variant  
**Status in catalog:** Incomplete  
**Applicable platforms:** Not Language-Specific, Web Based, Web Server

## Description

The product uses a WebSocket, but it does not properly verify that the source of data or communication is valid.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Implementation:** Enable CORS-like access restrictions by verifying the 'Origin' header during the WebSocket handshake.
- **Implementation:** Use a randomized CSRF token to verify requests.
- **Implementation:** Use TLS to securely communicate using 'wss' (WebSocket Secure) instead of 'ws'.
- **Architecture and Design:** Require user authentication prior to the WebSocket connection being established. For example, the WS library in Node has a 'verifyClient' function.
- **Implementation:** Leverage rate limiting to prevent against DoS. Use of the leaky bucket algorithm can help with this.
- **Implementation:** Use a library that provides restriction of the payload size. For example, WS library for Node includes 'maxPayloadoption' that can be set.
- **Implementation:** Treat data/input as untrusted in both directions and apply the same data/input sanitization as XSS, SQLi, etc.

## Related weaknesses

- CWE-346 (ChildOf)

## Source

- [CWE-1385 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/1385.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
