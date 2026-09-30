---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0048"
target_object: "T1005"
stix_relationship_id: "relationship--d77a4123-3d46-4317-8921-f6eb8c34c585"
---
# Relationship 7254: S0048 — uses → T1005

**Source object:** [[01 ATT&CK/S0048 - PinchDuke|S0048: PinchDuke]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1005 - Data from Local System|T1005: Data from Local System]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[PinchDuke](https://attack.mitre.org/software/S0048) collects user files from the compromised host based on predefined file extensions.(Citation: F-Secure The Dukes)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--d77a4123-3d46-4317-8921-f6eb8c34c585`.
