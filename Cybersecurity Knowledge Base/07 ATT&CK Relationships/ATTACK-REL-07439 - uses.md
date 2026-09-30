---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1031"
target_object: "T1059.003"
stix_relationship_id: "relationship--cc35f625-8da3-4d4d-a9bf-a600183d7230"
---
# Relationship 7439: S1031 — uses → T1059.003

**Source object:** [[01 ATT&CK/S1031 - PingPull|S1031: PingPull]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059.003 - Windows Command Shell|T1059.003: Windows Command Shell]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[PingPull](https://attack.mitre.org/software/S1031) can use `cmd.exe` to run various commands as a reverse shell.(Citation: Unit 42 PingPull Jun 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--cc35f625-8da3-4d4d-a9bf-a600183d7230`.
