---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0482"
target_object: "T1059.006"
stix_relationship_id: "relationship--677878af-62d4-4407-bbe6-551b7906a366"
---
# Relationship 9011: S0482 — uses → T1059.006

**Source object:** [[01 ATT&CK/S0482 - Bundlore|S0482: Bundlore]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059.006 - Python|T1059.006: Python]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Bundlore](https://attack.mitre.org/software/S0482) has used Python scripts to execute payloads.(Citation: MacKeeper Bundlore Apr 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--677878af-62d4-4407-bbe6-551b7906a366`.
