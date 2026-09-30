---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0453"
target_object: "T1027.015"
stix_relationship_id: "relationship--1927ea49-6d20-49d3-abf2-95e9122bf332"
---
# Relationship 9053: S0453 — uses → T1027.015

**Source object:** [[01 ATT&CK/S0453 - Pony|S0453: Pony]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1027.015 - Compression|T1027.015: Compression]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Pony](https://attack.mitre.org/software/S0453) attachments have been delivered via compressed archive files.(Citation: Malwarebytes Pony April 2016)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--1927ea49-6d20-49d3-abf2-95e9122bf332`.
