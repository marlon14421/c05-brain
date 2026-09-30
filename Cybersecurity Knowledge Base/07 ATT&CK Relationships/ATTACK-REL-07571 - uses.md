---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0339"
target_object: "T1059.003"
stix_relationship_id: "relationship--4261a057-4985-4180-8871-59c5b76e8a20"
---
# Relationship 7571: S0339 — uses → T1059.003

**Source object:** [[01 ATT&CK/S0339 - Micropsia|S0339: Micropsia]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059.003 - Windows Command Shell|T1059.003: Windows Command Shell]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Micropsia](https://attack.mitre.org/software/S0339) creates a command-line shell using cmd.exe.(Citation: Radware Micropsia July 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--4261a057-4985-4180-8871-59c5b76e8a20`.
