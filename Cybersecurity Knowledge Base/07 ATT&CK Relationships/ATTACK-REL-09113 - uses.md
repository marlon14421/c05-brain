---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0106"
target_object: "T1564.001"
stix_relationship_id: "relationship--48141016-3fc6-46af-9f93-b52439ed78ea"
---
# Relationship 9113: G0106 — uses → T1564.001

**Source object:** [[01 ATT&CK/G0106 - Rocke|G0106: Rocke]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1564.001 - Hidden Files and Directories|T1564.001: Hidden Files and Directories]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Rocke](https://attack.mitre.org/groups/G0106) downloaded a file "libprocesshider", which could hide files on the target system.(Citation: Talos Rocke August 2018)(Citation: Unit 42 Rocke January 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--48141016-3fc6-46af-9f93-b52439ed78ea`.
