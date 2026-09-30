---
type: "Attack Pattern"
source: "MITRE CAPEC"
id: "CAPEC-471"
status: "Stable"
---
# CAPEC-471: Search Order Hijacking

**Abstraction:** Detailed  
**Catalog severity:** Medium  
**Catalog likelihood:** Not stated

## Description

An adversary exploits a weakness in an application's specification of external libraries to exploit the functionality of the loader where the process loading the library searches first in the same directory in which the process binary resides and then in other directories. Exploitation of this preferential search order can allow an attacker to make the loading process load the adversary's rogue library rather than the legitimate library. This attack can be leveraged with many different libraries and with many different loading processes. No forensic trails are left in the system's registry or file system that an incorrect library had been loaded.

## Defensive interpretation

This catalog entry describes an attack pattern for threat modeling and defensive analysis. Map the conditions to assets, entry points, and controls in your own environment. Prioritize prevention, safe validation, logging, and incident response; this summary is not an execution guide and does not prove an active threat.

## Source

- [CAPEC-471 on capec.mitre.org](https://capec.mitre.org/data/definitions/471.html)
- Dataset: [MITRE CAPEC catalog](https://capec.mitre.org/data/downloads.html), version 3.9 (retrieved 2026-09-30).
