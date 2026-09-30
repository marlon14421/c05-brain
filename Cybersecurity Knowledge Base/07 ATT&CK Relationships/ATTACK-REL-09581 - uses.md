---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0129"
target_object: "T1003"
stix_relationship_id: "relationship--3d8b368c-57bc-4f36-808a-387a1e2cd3d9"
---
# Relationship 9581: G0129 — uses → T1003

**Source object:** [[01 ATT&CK/G0129 - Mustang Panda|G0129: Mustang Panda]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1003 - OS Credential Dumping|T1003: OS Credential Dumping]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Mustang Panda](https://attack.mitre.org/groups/G0129) utilized “Hdump” to dump credentials from memory.(Citation: Palo Alto Unit42 STATELY TAURUS TONESHELL September 2023)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--3d8b368c-57bc-4f36-808a-387a1e2cd3d9`.
