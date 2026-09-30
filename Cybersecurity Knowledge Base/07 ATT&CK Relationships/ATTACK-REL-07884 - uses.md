---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0380"
target_object: "T1561.001"
stix_relationship_id: "relationship--d2041a67-d846-4a1b-b704-4e437baa731a"
---
# Relationship 7884: S0380 — uses → T1561.001

**Source object:** [[01 ATT&CK/S0380 - StoneDrill|S0380: StoneDrill]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1561.001 - Disk Content Wipe|T1561.001: Disk Content Wipe]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[StoneDrill](https://attack.mitre.org/software/S0380) can wipe the accessible physical or logical drives of the infected machine.(Citation: Symantec Elfin Mar 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--d2041a67-d846-4a1b-b704-4e437baa731a`.
