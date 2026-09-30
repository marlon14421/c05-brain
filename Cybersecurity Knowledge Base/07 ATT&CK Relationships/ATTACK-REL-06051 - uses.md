---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0239"
target_object: "T1087.001"
stix_relationship_id: "relationship--a35c951b-5987-4028-b002-a2078ad9c0a7"
---
# Relationship 6051: S0239 — uses → T1087.001

**Source object:** [[01 ATT&CK/S0239 - Bankshot|S0239: Bankshot]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1087.001 - Local Account|T1087.001: Local Account]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Bankshot](https://attack.mitre.org/software/S0239) gathers domain and account names/information through process monitoring.(Citation: McAfee Bankshot)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--a35c951b-5987-4028-b002-a2078ad9c0a7`.
