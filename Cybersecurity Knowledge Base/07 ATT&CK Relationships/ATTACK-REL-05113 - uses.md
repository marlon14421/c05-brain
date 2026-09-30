---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0005"
target_object: "T1027.013"
stix_relationship_id: "relationship--d6de484e-a1f6-43cb-a506-ec4888e69bdd"
---
# Relationship 5113: C0005 — uses → T1027.013

**Source object:** [[01 ATT&CK/C0005 - Operation Spalax|C0005: Operation Spalax]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1027.013 - Encrypted-Encoded File|T1027.013: Encrypted/Encoded File]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

For [Operation Spalax](https://attack.mitre.org/campaigns/C0005), the threat actors used XOR-encrypted payloads.(Citation: ESET Operation Spalax Jan 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--d6de484e-a1f6-43cb-a506-ec4888e69bdd`.
