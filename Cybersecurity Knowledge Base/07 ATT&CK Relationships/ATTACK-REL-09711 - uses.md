---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0032"
target_object: "T1070.004"
stix_relationship_id: "relationship--979812c4-939e-4a7e-96b3-348028db10ce"
---
# Relationship 9711: G0032 — uses → T1070.004

**Source object:** [[01 ATT&CK/G0032 - Lazarus Group|G0032: Lazarus Group]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1070.004 - File Deletion|T1070.004: File Deletion]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Lazarus Group](https://attack.mitre.org/groups/G0032) malware has deleted files in various ways, including "suicide scripts" to delete malware binaries from the victim. [Lazarus Group](https://attack.mitre.org/groups/G0032) also uses secure file deletion to delete files from the victim.(Citation: Novetta Blockbuster)(Citation: McAfee GhostSecret)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--979812c4-939e-4a7e-96b3-348028db10ce`.
