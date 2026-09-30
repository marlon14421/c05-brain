---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0220"
target_object: "T1110"
stix_relationship_id: "relationship--49c17cdc-72a5-442d-b153-2cc9f9cf059d"
---
# Relationship 6397: S0220 — uses → T1110

**Source object:** [[01 ATT&CK/S0220 - Chaos|S0220: Chaos]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1110 - Brute Force|T1110: Brute Force]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Chaos](https://attack.mitre.org/software/S0220) conducts brute force attacks against SSH services to gain initial access.(Citation: Chaos Stolen Backdoor)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--49c17cdc-72a5-442d-b153-2cc9f9cf059d`.
