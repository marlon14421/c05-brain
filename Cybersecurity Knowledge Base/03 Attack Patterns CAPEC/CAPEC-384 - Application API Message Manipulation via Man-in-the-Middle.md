---
type: "Attack Pattern"
source: "MITRE CAPEC"
id: "CAPEC-384"
status: "Draft"
---
# CAPEC-384: Application API Message Manipulation via Man-in-the-Middle

**Abstraction:** Standard  
**Catalog severity:** Low  
**Catalog likelihood:** Not stated

## Description

An attacker manipulates either egress or ingress data from a client within an application framework in order to change the content of messages. Performing this attack can allow the attacker to gain unauthorized privileges within the application, or conduct attacks such as phishing, deceptive strategies to spread malware, or traditional web-application attacks. The techniques require use of specialized software that allow the attacker to perform adversary-in-the-middle (CAPEC-94) communications between the web browser and the remote system. Despite the use of AiTH software, the attack is actually directed at the server, as the client is one node in a series of content brokers that pass information along to the application framework. Additionally, it is not true "Adversary-in-the-Middle" attack at the network layer, but an application-layer attack the root cause of which is the master applications trust in the integrity of code supplied by the client.

## Defensive interpretation

This catalog entry describes an attack pattern for threat modeling and defensive analysis. Map the conditions to assets, entry points, and controls in your own environment. Prioritize prevention, safe validation, logging, and incident response; this summary is not an execution guide and does not prove an active threat.

## Source

- [CAPEC-384 on capec.mitre.org](https://capec.mitre.org/data/definitions/384.html)
- Dataset: [MITRE CAPEC catalog](https://capec.mitre.org/data/downloads.html), version 3.9 (retrieved 2026-09-30).
