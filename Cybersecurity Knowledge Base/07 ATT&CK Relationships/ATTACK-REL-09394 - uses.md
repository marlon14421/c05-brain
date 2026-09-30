---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0092"
target_object: "T1559.002"
stix_relationship_id: "relationship--f0e944fa-6dba-47c3-920a-cf7bad2d3bc5"
---
# Relationship 9394: G0092 — uses → T1559.002

**Source object:** [[01 ATT&CK/G0092 - TA505|G0092: TA505]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1559.002 - Dynamic Data Exchange|T1559.002: Dynamic Data Exchange]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[TA505](https://attack.mitre.org/groups/G0092) has leveraged malicious Word documents that abused DDE.(Citation: Proofpoint TA505 June 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--f0e944fa-6dba-47c3-920a-cf7bad2d3bc5`.
