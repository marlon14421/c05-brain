---
type: "Attack Pattern"
source: "MITRE CAPEC"
id: "CAPEC-142"
status: "Draft"
---
# CAPEC-142: DNS Cache Poisoning

**Abstraction:** Detailed  
**Catalog severity:** High  
**Catalog likelihood:** High

## Description

A domain name server translates a domain name (such as www.example.com) into an IP address that Internet hosts use to contact Internet resources. An adversary modifies a public DNS cache to cause certain names to resolve to incorrect addresses that the adversary specifies. The result is that client applications that rely upon the targeted cache for domain name resolution will be directed not to the actual address of the specified domain name but to some other address. Adversaries can use this to herd clients to sites that install malware on the victim's computer or to masquerade as part of a Pharming attack.

## Defensive interpretation

This catalog entry describes an attack pattern for threat modeling and defensive analysis. Map the conditions to assets, entry points, and controls in your own environment. Prioritize prevention, safe validation, logging, and incident response; this summary is not an execution guide and does not prove an active threat.

## Source

- [CAPEC-142 on capec.mitre.org](https://capec.mitre.org/data/definitions/142.html)
- Dataset: [MITRE CAPEC catalog](https://capec.mitre.org/data/downloads.html), version 3.9 (retrieved 2026-09-30).
