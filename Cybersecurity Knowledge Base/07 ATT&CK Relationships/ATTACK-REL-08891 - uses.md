---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0016"
target_object: "T1059.005"
stix_relationship_id: "relationship--bc0704ff-406d-4be2-90ef-6a667041365f"
---
# Relationship 8891: C0016 — uses → T1059.005

**Source object:** [[01 ATT&CK/C0016 - Operation Dust Storm|C0016: Operation Dust Storm]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059.005 - Visual Basic|T1059.005: Visual Basic]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

During [Operation Dust Storm](https://attack.mitre.org/campaigns/C0016), the threat actors used Visual Basic scripts.(Citation: Cylance Dust Storm)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--bc0704ff-406d-4be2-90ef-6a667041365f`.
