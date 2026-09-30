---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1071"
target_object: "T1558.002"
stix_relationship_id: "relationship--6a2ade56-5413-424b-9d8e-ba91267fade7"
---
# Relationship 7048: S1071 — uses → T1558.002

**Source object:** [[01 ATT&CK/S1071 - Rubeus|S1071: Rubeus]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1558.002 - Silver Ticket|T1558.002: Silver Ticket]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Rubeus](https://attack.mitre.org/software/S1071) can create silver tickets.(Citation: GitHub Rubeus March 2023)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--6a2ade56-5413-424b-9d8e-ba91267fade7`.
