---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1159"
target_object: "T1059.003"
stix_relationship_id: "relationship--ac94eab0-5d4e-419d-806b-fb085a532f31"
---
# Relationship 6210: S1159 — uses → T1059.003

**Source object:** [[01 ATT&CK/S1159 - DUSTTRAP|S1159: DUSTTRAP]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059.003 - Windows Command Shell|T1059.003: Windows Command Shell]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[DUSTTRAP](https://attack.mitre.org/software/S1159) can execute commands via `cmd.exe`.(Citation: Google Cloud APT41 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--ac94eab0-5d4e-419d-806b-fb085a532f31`.
