---
type: "Attack Pattern"
source: "MITRE CAPEC"
id: "CAPEC-630"
status: "Draft"
---
# CAPEC-630: TypoSquatting

**Abstraction:** Detailed  
**Catalog severity:** Medium  
**Catalog likelihood:** Low

## Description

An adversary registers a domain name with at least one character different than a trusted domain. A TypoSquatting attack takes advantage of instances where a user mistypes a URL (e.g. www.goggle.com) or not does visually verify a URL before clicking on it (e.g. phishing attack). As a result, the user is directed to an adversary-controlled destination. TypoSquatting does not require an attack against the trusted domain or complicated reverse engineering.

## Defensive interpretation

This catalog entry describes an attack pattern for threat modeling and defensive analysis. Map the conditions to assets, entry points, and controls in your own environment. Prioritize prevention, safe validation, logging, and incident response; this summary is not an execution guide and does not prove an active threat.

## Source

- [CAPEC-630 on capec.mitre.org](https://capec.mitre.org/data/definitions/630.html)
- Dataset: [MITRE CAPEC catalog](https://capec.mitre.org/data/downloads.html), version 3.9 (retrieved 2026-09-30).
