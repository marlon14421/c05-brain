---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1071"
target_object: "T1482"
stix_relationship_id: "relationship--3376df6e-0a4d-4a28-98b9-5d40ef092588"
---
# Relationship 7738: S1071 — uses → T1482

**Source object:** [[01 ATT&CK/S1071 - Rubeus|S1071: Rubeus]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1482 - Domain Trust Discovery|T1482: Domain Trust Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Rubeus](https://attack.mitre.org/software/S1071) can gather information about domain trusts.(Citation: DFIR Ryuk's Return October 2020)(Citation: DFIR Ryuk 2 Hour Speed Run November 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--3376df6e-0a4d-4a28-98b9-5d40ef092588`.
