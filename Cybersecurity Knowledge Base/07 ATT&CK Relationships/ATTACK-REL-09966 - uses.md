---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0344"
target_object: "T1134.002"
stix_relationship_id: "relationship--00d3d6a8-c711-4bb5-bf0a-e17c0ecac8c8"
---
# Relationship 9966: S0344 — uses → T1134.002

**Source object:** [[01 ATT&CK/S0344 - Azorult|S0344: Azorult]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1134.002 - Create Process with Token|T1134.002: Create Process with Token]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Azorult](https://attack.mitre.org/software/S0344) can call WTSQueryUserToken and CreateProcessAsUser to start a new process with local system privileges.(Citation: Unit42 Azorult Nov 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--00d3d6a8-c711-4bb5-bf0a-e17c0ecac8c8`.
