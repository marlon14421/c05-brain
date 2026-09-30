---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0035"
target_object: "T1087.002"
stix_relationship_id: "relationship--fa6f9dc7-e984-411a-9ce4-a822d4213bc6"
---
# Relationship 8797: G0035 — uses → T1087.002

**Source object:** [[01 ATT&CK/G0035 - Dragonfly|G0035: Dragonfly]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1087.002 - Domain Account|T1087.002: Domain Account]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Dragonfly](https://attack.mitre.org/groups/G0035) has used batch scripts to enumerate users on a victim domain controller.(Citation: US-CERT TA18-074A)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--fa6f9dc7-e984-411a-9ce4-a822d4213bc6`.
