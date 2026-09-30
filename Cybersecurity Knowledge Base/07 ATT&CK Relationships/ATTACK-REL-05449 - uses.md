---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0120"
target_object: "T1059.007"
stix_relationship_id: "relationship--ea3b16db-6b34-4171-9dec-7ce618f49dee"
---
# Relationship 5449: G0120 — uses → T1059.007

**Source object:** [[01 ATT&CK/G0120 - Evilnum|G0120: Evilnum]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059.007 - JavaScript|T1059.007: JavaScript]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Evilnum](https://attack.mitre.org/groups/G0120) has used malicious JavaScript files on the victim's machine.(Citation: ESET EvilNum July 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--ea3b16db-6b34-4171-9dec-7ce618f49dee`.
