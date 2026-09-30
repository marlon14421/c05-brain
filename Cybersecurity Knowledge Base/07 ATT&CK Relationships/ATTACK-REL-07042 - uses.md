---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S9032"
target_object: "T1678"
stix_relationship_id: "relationship--105235ae-d06d-47ed-8eea-8237bd1d7397"
---
# Relationship 7042: S9032 — uses → T1678

**Source object:** [[01 ATT&CK/S9032 - MuddyViper|S9032: MuddyViper]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1678 - Delay Execution|T1678: Delay Execution]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[MuddyViper](https://attack.mitre.org/software/S9032) has the ability to sleep for a certain amount of time, with the default being one minute.(Citation: ESET_MuddyWater_Dec2025)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--105235ae-d06d-47ed-8eea-8237bd1d7397`.
