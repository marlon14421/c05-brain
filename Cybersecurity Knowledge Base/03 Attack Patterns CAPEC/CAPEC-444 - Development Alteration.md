---
type: "Attack Pattern"
source: "MITRE CAPEC"
id: "CAPEC-444"
status: "Stable"
---
# CAPEC-444: Development Alteration

**Abstraction:** Standard  
**Catalog severity:** High  
**Catalog likelihood:** Medium

## Description

An adversary modifies a technology, product, or component during its development to acheive a negative impact once the system is deployed. The goal of the adversary is to modify the system in such a way that the negative impact can be leveraged when the system is later deployed. Development alteration attacks may include attacks that insert malicious logic into the system's software, modify or replace hardware components, and other attacks which negatively impact the system during development. These attacks generally require insider access to modify source code or to tamper with hardware components. The product is then delivered to the user where the negative impact can be leveraged at a later time.

## Defensive interpretation

This catalog entry describes an attack pattern for threat modeling and defensive analysis. Map the conditions to assets, entry points, and controls in your own environment. Prioritize prevention, safe validation, logging, and incident response; this summary is not an execution guide and does not prove an active threat.

## Source

- [CAPEC-444 on capec.mitre.org](https://capec.mitre.org/data/definitions/444.html)
- Dataset: [MITRE CAPEC catalog](https://capec.mitre.org/data/downloads.html), version 3.9 (retrieved 2026-09-30).
