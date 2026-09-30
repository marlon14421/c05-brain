---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0106"
target_object: "T1082"
stix_relationship_id: "relationship--322876d6-1b49-43d8-9e4a-590919d1f930"
---
# Relationship 5497: G0106 — uses → T1082

**Source object:** [[01 ATT&CK/G0106 - Rocke|G0106: Rocke]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1082 - System Information Discovery|T1082: System Information Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Rocke](https://attack.mitre.org/groups/G0106) has used uname -m to collect the name and information about the infected system's kernel.(Citation: Anomali Rocke March 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--322876d6-1b49-43d8-9e4a-590919d1f930`.
