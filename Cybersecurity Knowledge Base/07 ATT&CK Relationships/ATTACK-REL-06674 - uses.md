---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0034"
target_object: "T1608.001"
stix_relationship_id: "relationship--018ed869-7916-41c3-b60b-818bac4e6ce5"
---
# Relationship 6674: G0034 — uses → T1608.001

**Source object:** [[01 ATT&CK/G0034 - Sandworm Team|G0034: Sandworm Team]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1608.001 - Upload Malware|T1608.001: Upload Malware]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Sandworm Team](https://attack.mitre.org/groups/G0034) staged compromised versions of legitimate software installers in forums to enable initial access to executing user.(Citation: mandiant_apt44_unearthing_sandworm)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--018ed869-7916-41c3-b60b-818bac4e6ce5`.
