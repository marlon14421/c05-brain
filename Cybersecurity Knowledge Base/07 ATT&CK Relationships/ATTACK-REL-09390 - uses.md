---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1016"
target_object: "T1136.001"
stix_relationship_id: "relationship--4248d8aa-eec4-4fd3-9707-ca1ed85bf5c5"
---
# Relationship 9390: G1016 — uses → T1136.001

**Source object:** [[01 ATT&CK/G1016 - FIN13|G1016: FIN13]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1136.001 - Local Account|T1136.001: Local Account]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[FIN13](https://attack.mitre.org/groups/G1016) has created MS-SQL local accounts in a compromised network.(Citation: Sygnia Elephant Beetle Jan 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--4248d8aa-eec4-4fd3-9707-ca1ed85bf5c5`.
