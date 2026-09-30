---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0482"
target_object: "T1057"
stix_relationship_id: "relationship--1e10af38-1695-45ab-8db2-8cd476a58a45"
---
# Relationship 8401: S0482 — uses → T1057

**Source object:** [[01 ATT&CK/S0482 - Bundlore|S0482: Bundlore]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1057 - Process Discovery|T1057: Process Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Bundlore](https://attack.mitre.org/software/S0482) has used the ps command to list processes.(Citation: MacKeeper Bundlore Apr 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--1e10af38-1695-45ab-8db2-8cd476a58a45`.
