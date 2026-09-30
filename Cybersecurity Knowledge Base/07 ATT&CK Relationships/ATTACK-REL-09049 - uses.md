---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0400"
target_object: "T1486"
stix_relationship_id: "relationship--e2fd8460-85cf-42b3-acee-7151758ee55a"
---
# Relationship 9049: S0400 — uses → T1486

**Source object:** [[01 ATT&CK/S0400 - RobbinHood|S0400: RobbinHood]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1486 - Data Encrypted for Impact|T1486: Data Encrypted for Impact]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[RobbinHood](https://attack.mitre.org/software/S0400) will search for an RSA encryption key and then perform its encryption process on the system files.(Citation: CarbonBlack RobbinHood May 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e2fd8460-85cf-42b3-acee-7151758ee55a`.
