---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0124"
target_object: "T1059.003"
stix_relationship_id: "relationship--0c56b369-b665-4001-87ff-d27ae135cc64"
---
# Relationship 7941: S0124 — uses → T1059.003

**Source object:** [[01 ATT&CK/S0124 - Pisloader|S0124: Pisloader]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059.003 - Windows Command Shell|T1059.003: Windows Command Shell]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Pisloader](https://attack.mitre.org/software/S0124) uses cmd.exe to set the Registry Run key value. It also has a command to spawn a command shell.(Citation: Palo Alto DNS Requests)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--0c56b369-b665-4001-87ff-d27ae135cc64`.
