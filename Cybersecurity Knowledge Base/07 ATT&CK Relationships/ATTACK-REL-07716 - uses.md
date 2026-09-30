---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0067"
target_object: "T1059.003"
stix_relationship_id: "relationship--cae6bbd0-d00e-4cc4-872a-d3ac9cc97684"
---
# Relationship 7716: G0067 — uses → T1059.003

**Source object:** [[01 ATT&CK/G0067 - APT37|G0067: APT37]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059.003 - Windows Command Shell|T1059.003: Windows Command Shell]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[APT37](https://attack.mitre.org/groups/G0067) has used the command-line interface.(Citation: FireEye APT37 Feb 2018)(Citation: Talos Group123)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--cae6bbd0-d00e-4cc4-872a-d3ac9cc97684`.
