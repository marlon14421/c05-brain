---
type: "Attack Pattern"
source: "MITRE CAPEC"
id: "CAPEC-613"
status: "Draft"
---
# CAPEC-613: WiFi SSID Tracking

**Abstraction:** Detailed  
**Catalog severity:** Low  
**Catalog likelihood:** Not stated

## Description

In this attack scenario, the attacker passively listens for WiFi management frame messages containing the Service Set Identifier (SSID) for the WiFi network. These messages are frequently transmitted by WiFi access points (e.g., the retransmission device) as well as by clients that are accessing the network (e.g., the handset/mobile device). Once the attacker is able to associate an SSID with a particular user or set of users (for example, when attending a public event), the attacker can then scan for this SSID to track that user in the future.

## Defensive interpretation

This catalog entry describes an attack pattern for threat modeling and defensive analysis. Map the conditions to assets, entry points, and controls in your own environment. Prioritize prevention, safe validation, logging, and incident response; this summary is not an execution guide and does not prove an active threat.

## Source

- [CAPEC-613 on capec.mitre.org](https://capec.mitre.org/data/definitions/613.html)
- Dataset: [MITRE CAPEC catalog](https://capec.mitre.org/data/downloads.html), version 3.9 (retrieved 2026-09-30).
