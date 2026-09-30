---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0037"
target_object: "T1573.001"
stix_relationship_id: "relationship--3ebc8829-f260-4d75-817a-cd23a4ebb194"
---
# Relationship 9010: S0037 — uses → T1573.001

**Source object:** [[01 ATT&CK/S0037 - HAMMERTOSS|S0037: HAMMERTOSS]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1573.001 - Symmetric Cryptography|T1573.001: Symmetric Cryptography]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

Before being appended to image files, [HAMMERTOSS](https://attack.mitre.org/software/S0037) commands are encrypted with a key composed of both a hard-coded value and a string contained on that day's tweet. To decrypt the commands, an investigator would need access to the intended malware sample, the day's tweet, and the image file containing the command.(Citation: FireEye APT29)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--3ebc8829-f260-4d75-817a-cd23a4ebb194`.
