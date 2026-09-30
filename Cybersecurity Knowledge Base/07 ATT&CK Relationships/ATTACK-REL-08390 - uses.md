---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0129"
target_object: "T1003.001"
stix_relationship_id: "relationship--714ae0c0-aa49-45c6-a977-c86783f057dc"
---
# Relationship 8390: G0129 — uses → T1003.001

**Source object:** [[01 ATT&CK/G0129 - Mustang Panda|G0129: Mustang Panda]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1003.001 - LSASS Memory|T1003.001: LSASS Memory]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Mustang Panda](https://attack.mitre.org/groups/G0129) has harvested credentials from memory of lssas.exe with [Mimikatz](https://attack.mitre.org/software/S0002).(Citation: Palo Alto Unit42 STATELY TAURUS TONESHELL September 2023)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--714ae0c0-aa49-45c6-a977-c86783f057dc`.
