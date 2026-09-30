---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0679"
target_object: "T1546.015"
stix_relationship_id: "relationship--8604868a-8226-4c03-a5b2-bedfc4020865"
---
# Relationship 7642: S0679 — uses → T1546.015

**Source object:** [[01 ATT&CK/S0679 - Ferocious|S0679: Ferocious]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1546.015 - Component Object Model Hijacking|T1546.015: Component Object Model Hijacking]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Ferocious](https://attack.mitre.org/software/S0679) can use COM hijacking to establish persistence.(Citation: Kaspersky WIRTE November 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--8604868a-8226-4c03-a5b2-bedfc4020865`.
