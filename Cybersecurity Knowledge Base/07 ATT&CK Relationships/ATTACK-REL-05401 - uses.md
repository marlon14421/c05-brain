---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1089"
target_object: "T1059.003"
stix_relationship_id: "relationship--e1172f5d-5645-4963-b89c-fd975c1f2798"
---
# Relationship 5401: S1089 — uses → T1059.003

**Source object:** [[01 ATT&CK/S1089 - SharpDisco|S1089: SharpDisco]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059.003 - Windows Command Shell|T1059.003: Windows Command Shell]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[SharpDisco](https://attack.mitre.org/software/S1089) can use `cmd.exe` to execute plugins and to send command output to specified SMB shares.(Citation: MoustachedBouncer ESET August 2023)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e1172f5d-5645-4963-b89c-fd975c1f2798`.
