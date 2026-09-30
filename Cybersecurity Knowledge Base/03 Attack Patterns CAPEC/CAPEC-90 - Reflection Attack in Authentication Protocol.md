---
type: "Attack Pattern"
source: "MITRE CAPEC"
id: "CAPEC-90"
status: "Draft"
---
# CAPEC-90: Reflection Attack in Authentication Protocol

**Abstraction:** Standard  
**Catalog severity:** High  
**Catalog likelihood:** High

## Description

An adversary can abuse an authentication protocol susceptible to reflection attack in order to defeat it. Doing so allows the adversary illegitimate access to the target system, without possessing the requisite credentials. Reflection attacks are of great concern to authentication protocols that rely on a challenge-handshake or similar mechanism. An adversary can impersonate a legitimate user and can gain illegitimate access to the system by successfully mounting a reflection attack during authentication.

## Defensive interpretation

This catalog entry describes an attack pattern for threat modeling and defensive analysis. Map the conditions to assets, entry points, and controls in your own environment. Prioritize prevention, safe validation, logging, and incident response; this summary is not an execution guide and does not prove an active threat.

## Source

- [CAPEC-90 on capec.mitre.org](https://capec.mitre.org/data/definitions/90.html)
- Dataset: [MITRE CAPEC catalog](https://capec.mitre.org/data/downloads.html), version 3.9 (retrieved 2026-09-30).
