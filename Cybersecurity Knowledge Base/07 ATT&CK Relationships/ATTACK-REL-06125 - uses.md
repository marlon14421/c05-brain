---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1160"
target_object: "T1016"
stix_relationship_id: "relationship--1cc9d9cb-1671-44a3-916c-bf191490946c"
---
# Relationship 6125: S1160 — uses → T1016

**Source object:** [[01 ATT&CK/S1160 - Latrodectus|S1160: Latrodectus]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1016 - System Network Configuration Discovery|T1016: System Network Configuration Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Latrodectus](https://attack.mitre.org/software/S1160) can discover the IP and MAC address of a targeted host.(Citation: Elastic Latrodectus May 2024)(Citation: Bitsight Latrodectus June 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--1cc9d9cb-1671-44a3-916c-bf191490946c`.
