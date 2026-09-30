---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0005"
target_object: "T1102.002"
stix_relationship_id: "relationship--5a49400c-2003-463c-8e6e-97b79f560675"
---
# Relationship 8501: G0005 — uses → T1102.002

**Source object:** [[01 ATT&CK/G0005 - APT12|G0005: APT12]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1102.002 - Bidirectional Communication|T1102.002: Bidirectional Communication]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[APT12](https://attack.mitre.org/groups/G0005) has used blogs and WordPress for C2 infrastructure.(Citation: Meyers Numbered Panda)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--5a49400c-2003-463c-8e6e-97b79f560675`.
