---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0493"
target_object: "T1497.003"
stix_relationship_id: "relationship--bd289f02-1354-423e-b5e4-7aca35ec9d8a"
---
# Relationship 7763: S0493 — uses → T1497.003

**Source object:** [[01 ATT&CK/S0493 - GoldenSpy|S0493: GoldenSpy]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1497.003 - Time Based Checks|T1497.003: Time Based Checks]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[GoldenSpy](https://attack.mitre.org/software/S0493)'s installer has delayed installation of [GoldenSpy](https://attack.mitre.org/software/S0493) for two hours after it reaches a victim system.(Citation: Trustwave GoldenSpy June 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--bd289f02-1354-423e-b5e4-7aca35ec9d8a`.
