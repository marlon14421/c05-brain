---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0040"
target_object: "T1518.001"
stix_relationship_id: "relationship--6a5bc2dd-2132-4af0-9b12-0e781971d96c"
---
# Relationship 7123: G0040 — uses → T1518.001

**Source object:** [[01 ATT&CK/G0040 - Patchwork|G0040: Patchwork]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1518.001 - Security Software Discovery|T1518.001: Security Software Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Patchwork](https://attack.mitre.org/groups/G0040) scanned the “Program Files” directories for a directory with the string “Total Security” (the installation path of the “360 Total Security” antivirus tool).(Citation: Cymmetria Patchwork)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--6a5bc2dd-2132-4af0-9b12-0e781971d96c`.
