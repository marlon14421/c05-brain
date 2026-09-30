---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0434"
target_object: "T1496.001"
stix_relationship_id: "relationship--8f0e7661-fa5d-47c4-84b0-44cd31b49764"
---
# Relationship 6016: S0434 — uses → T1496.001

**Source object:** [[01 ATT&CK/S0434 - Imminent Monitor|S0434: Imminent Monitor]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1496.001 - Compute Hijacking|T1496.001: Compute Hijacking]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Imminent Monitor](https://attack.mitre.org/software/S0434) has the capability to run a cryptocurrency miner on the victim machine.(Citation: Imminent Unit42 Dec2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--8f0e7661-fa5d-47c4-84b0-44cd31b49764`.
