---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0023"
target_object: "T1071.001"
stix_relationship_id: "relationship--3a9abcd5-52ba-44f1-96a5-1593f816b9f0"
---
# Relationship 7607: S0023 — uses → T1071.001

**Source object:** [[01 ATT&CK/S0023 - CHOPSTICK|S0023: CHOPSTICK]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1071.001 - Web Protocols|T1071.001: Web Protocols]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

Various implementations of [CHOPSTICK](https://attack.mitre.org/software/S0023) communicate with C2 over HTTP.(Citation: ESET Sednit Part 2)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--3a9abcd5-52ba-44f1-96a5-1593f816b9f0`.
