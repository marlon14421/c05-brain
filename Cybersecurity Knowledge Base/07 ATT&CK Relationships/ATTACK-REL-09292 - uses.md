---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1068"
target_object: "T1059.003"
stix_relationship_id: "relationship--e58bc387-6540-4976-8c12-73ddf15084ed"
---
# Relationship 9292: S1068 — uses → T1059.003

**Source object:** [[01 ATT&CK/S1068 - BlackCat|S1068: BlackCat]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059.003 - Windows Command Shell|T1059.003: Windows Command Shell]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[BlackCat](https://attack.mitre.org/software/S1068) can execute commands on a compromised network with the use of `cmd.exe`.(Citation: Microsoft BlackCat Jun 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e58bc387-6540-4976-8c12-73ddf15084ed`.
