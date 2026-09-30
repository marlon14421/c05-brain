---
type: "Attack Pattern"
source: "MITRE CAPEC"
id: "CAPEC-31"
status: "Draft"
---
# CAPEC-31: Accessing/Intercepting/Modifying HTTP Cookies

**Abstraction:** Detailed  
**Catalog severity:** High  
**Catalog likelihood:** High

## Description

This attack relies on the use of HTTP Cookies to store credentials, state information and other critical data on client systems. There are several different forms of this attack. The first form of this attack involves accessing HTTP Cookies to mine for potentially sensitive data contained therein. The second form involves intercepting this data as it is transmitted from client to server. This intercepted information is then used by the adversary to impersonate the remote user/session. The third form is when the cookie's content is modified by the adversary before it is sent back to the server. Here the adversary seeks to convince the target server to operate on this falsified information.

## Defensive interpretation

This catalog entry describes an attack pattern for threat modeling and defensive analysis. Map the conditions to assets, entry points, and controls in your own environment. Prioritize prevention, safe validation, logging, and incident response; this summary is not an execution guide and does not prove an active threat.

## Source

- [CAPEC-31 on capec.mitre.org](https://capec.mitre.org/data/definitions/31.html)
- Dataset: [MITRE CAPEC catalog](https://capec.mitre.org/data/downloads.html), version 3.9 (retrieved 2026-09-30).
