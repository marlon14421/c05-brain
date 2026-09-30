---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0269"
target_object: "T1053.005"
stix_relationship_id: "relationship--ff2b7bc3-d6ca-488a-bdd5-1f2f27dfc8bd"
---
# Relationship 8676: S0269 — uses → T1053.005

**Source object:** [[01 ATT&CK/S0269 - QUADAGENT|S0269: QUADAGENT]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1053.005 - Scheduled Task|T1053.005: Scheduled Task]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[QUADAGENT](https://attack.mitre.org/software/S0269) creates a scheduled task to maintain persistence on the victim’s machine.(Citation: Unit 42 QUADAGENT July 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--ff2b7bc3-d6ca-488a-bdd5-1f2f27dfc8bd`.
