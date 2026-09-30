---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0155"
target_object: "T1012"
stix_relationship_id: "relationship--47f611f4-b9f0-42ef-9629-ee4a56e737ed"
---
# Relationship 9389: S0155 — uses → T1012

**Source object:** [[01 ATT&CK/S0155 - WINDSHIELD|S0155: WINDSHIELD]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1012 - Query Registry|T1012: Query Registry]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[WINDSHIELD](https://attack.mitre.org/software/S0155) can gather Registry values.(Citation: FireEye APT32 May 2017)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--47f611f4-b9f0-42ef-9629-ee4a56e737ed`.
