---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1028"
target_object: "T1059.003"
stix_relationship_id: "relationship--feb5dda0-1300-4e5b-9372-7d6b4d5473f3"
---
# Relationship 9795: S1028 — uses → T1059.003

**Source object:** [[01 ATT&CK/S1028 - Action RAT|S1028: Action RAT]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059.003 - Windows Command Shell|T1059.003: Windows Command Shell]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Action RAT](https://attack.mitre.org/software/S1028) can use `cmd.exe` to execute commands on an infected host.(Citation: MalwareBytes SideCopy Dec 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--feb5dda0-1300-4e5b-9372-7d6b4d5473f3`.
