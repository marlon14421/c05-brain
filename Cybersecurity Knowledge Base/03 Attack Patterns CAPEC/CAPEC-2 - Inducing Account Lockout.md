---
type: "Attack Pattern"
source: "MITRE CAPEC"
id: "CAPEC-2"
status: "Draft"
---
# CAPEC-2: Inducing Account Lockout

**Abstraction:** Standard  
**Catalog severity:** Medium  
**Catalog likelihood:** High

## Description

An attacker leverages the security functionality of the system aimed at thwarting potential attacks to launch a denial of service attack against a legitimate system user. Many systems, for instance, implement a password throttling mechanism that locks an account after a certain number of incorrect log in attempts. An attacker can leverage this throttling mechanism to lock a legitimate user out of their own account. The weakness that is being leveraged by an attacker is the very security feature that has been put in place to counteract attacks.

## Defensive interpretation

This catalog entry describes an attack pattern for threat modeling and defensive analysis. Map the conditions to assets, entry points, and controls in your own environment. Prioritize prevention, safe validation, logging, and incident response; this summary is not an execution guide and does not prove an active threat.

## Source

- [CAPEC-2 on capec.mitre.org](https://capec.mitre.org/data/definitions/2.html)
- Dataset: [MITRE CAPEC catalog](https://capec.mitre.org/data/downloads.html), version 3.9 (retrieved 2026-09-30).
