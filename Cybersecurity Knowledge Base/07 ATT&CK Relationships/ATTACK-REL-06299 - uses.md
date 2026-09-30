---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S9023"
target_object: "T1033"
stix_relationship_id: "relationship--59f27a62-6748-44d0-b9aa-ef976dd97502"
---
# Relationship 6299: S9023 — uses → T1033

**Source object:** [[01 ATT&CK/S9023 - HiddenFace|S9023: HiddenFace]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1033 - System Owner-User Discovery|T1033: System Owner/User Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[HiddenFace](https://attack.mitre.org/software/S9023) can collect the username associated with the compromised host.(Citation: ESET HiddenFace 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--59f27a62-6748-44d0-b9aa-ef976dd97502`.
