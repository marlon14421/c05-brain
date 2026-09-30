---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0333"
target_object: "T1059.003"
stix_relationship_id: "relationship--3aef452a-4ad9-4882-aebb-0043f2329f1d"
---
# Relationship 7213: S0333 — uses → T1059.003

**Source object:** [[01 ATT&CK/S0333 - UBoatRAT|S0333: UBoatRAT]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059.003 - Windows Command Shell|T1059.003: Windows Command Shell]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[UBoatRAT](https://attack.mitre.org/software/S0333) can start a command shell.(Citation: PaloAlto UBoatRAT Nov 2017)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--3aef452a-4ad9-4882-aebb-0043f2329f1d`.
