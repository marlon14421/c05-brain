---
type: "Attack Pattern"
source: "MITRE CAPEC"
id: "CAPEC-395"
status: "Draft"
---
# CAPEC-395: Bypassing Electronic Locks and Access Controls

**Abstraction:** Standard  
**Catalog severity:** Not stated  
**Catalog likelihood:** Not stated

## Description

An attacker exploits security assumptions to bypass electronic locks or other forms of access controls. Most attacks against electronic access controls follow similar methods but utilize different tools. Some electronic locks utilize magnetic strip cards, others employ RFID tags embedded within a card or badge, or may involve more sophisticated protections such as voice-print, thumb-print, or retinal biometrics. Magnetic Strip and RFID technologies are the most widespread because they are cost effective to deploy and more easily integrated with other electronic security measures. These technologies share common weaknesses that an attacker can exploit to gain access to a facility protected by the mechanisms via copying legitimate cards or badges, or generating new cards using reverse-engineered algorithms.

## Defensive interpretation

This catalog entry describes an attack pattern for threat modeling and defensive analysis. Map the conditions to assets, entry points, and controls in your own environment. Prioritize prevention, safe validation, logging, and incident response; this summary is not an execution guide and does not prove an active threat.

## Source

- [CAPEC-395 on capec.mitre.org](https://capec.mitre.org/data/definitions/395.html)
- Dataset: [MITRE CAPEC catalog](https://capec.mitre.org/data/downloads.html), version 3.9 (retrieved 2026-09-30).
