---
type: "Attack Pattern"
source: "MITRE CAPEC"
id: "CAPEC-383"
status: "Draft"
---
# CAPEC-383: Harvesting Information via API Event Monitoring

**Abstraction:** Detailed  
**Catalog severity:** Low  
**Catalog likelihood:** Not stated

## Description

An adversary hosts an event within an application framework and then monitors the data exchanged during the course of the event for the purpose of harvesting any important data leaked during the transactions. One example could be harvesting lists of usernames or userIDs for the purpose of sending spam messages to those users. One example of this type of attack involves the adversary creating an event within the sub-application. Assume the adversary hosts a "virtual sale" of rare items. As other users enter the event, the attacker records via AiTM (CAPEC-94) proxy the user_ids and usernames of everyone who attends. The adversary would then be able to spam those users within the application using an automated script.

## Defensive interpretation

This catalog entry describes an attack pattern for threat modeling and defensive analysis. Map the conditions to assets, entry points, and controls in your own environment. Prioritize prevention, safe validation, logging, and incident response; this summary is not an execution guide and does not prove an active threat.

## Source

- [CAPEC-383 on capec.mitre.org](https://capec.mitre.org/data/definitions/383.html)
- Dataset: [MITRE CAPEC catalog](https://capec.mitre.org/data/downloads.html), version 3.9 (retrieved 2026-09-30).
