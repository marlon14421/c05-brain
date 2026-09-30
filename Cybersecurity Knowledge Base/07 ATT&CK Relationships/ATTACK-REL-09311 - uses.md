---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0331"
target_object: "T1564.003"
stix_relationship_id: "relationship--75bd34c6-c8b3-4b5e-aac4-9e410515169c"
---
# Relationship 9311: S0331 — uses → T1564.003

**Source object:** [[01 ATT&CK/S0331 - Agent Tesla|S0331: Agent Tesla]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1564.003 - Hidden Window|T1564.003: Hidden Window]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Agent Tesla](https://attack.mitre.org/software/S0331) has used ProcessWindowStyle.Hidden to hide windows.(Citation: Malwarebytes Agent Tesla April 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--75bd34c6-c8b3-4b5e-aac4-9e410515169c`.
