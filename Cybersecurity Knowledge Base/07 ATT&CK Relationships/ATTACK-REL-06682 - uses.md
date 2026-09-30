---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0666"
target_object: "T1005"
stix_relationship_id: "relationship--a2c1921d-3d5d-4ec7-ab4d-4fe2e7d19e64"
---
# Relationship 6682: S0666 — uses → T1005

**Source object:** [[01 ATT&CK/S0666 - Gelsemium|S0666: Gelsemium]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1005 - Data from Local System|T1005: Data from Local System]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Gelsemium](https://attack.mitre.org/software/S0666) can collect data from a compromised host.(Citation: ESET Gelsemium June 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--a2c1921d-3d5d-4ec7-ab4d-4fe2e7d19e64`.
