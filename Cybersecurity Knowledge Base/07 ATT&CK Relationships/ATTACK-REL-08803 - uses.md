---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0584"
target_object: "T1218.007"
stix_relationship_id: "relationship--8d3f505a-35d6-4c79-afc3-88979d9e156c"
---
# Relationship 8803: S0584 — uses → T1218.007

**Source object:** [[01 ATT&CK/S0584 - AppleJeus|S0584: AppleJeus]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1218.007 - Msiexec|T1218.007: Msiexec]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[AppleJeus](https://attack.mitre.org/software/S0584) has been installed via MSI installer.(Citation: CISA AppleJeus Feb 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--8d3f505a-35d6-4c79-afc3-88979d9e156c`.
