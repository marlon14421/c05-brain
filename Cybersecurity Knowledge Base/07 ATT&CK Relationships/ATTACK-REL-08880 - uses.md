---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1135"
target_object: "T1059.003"
stix_relationship_id: "relationship--a0004fa0-4650-4875-aa11-78aa3b34c7ea"
---
# Relationship 8880: S1135 — uses → T1059.003

**Source object:** [[01 ATT&CK/S1135 - MultiLayer Wiper|S1135: MultiLayer Wiper]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059.003 - Windows Command Shell|T1059.003: Windows Command Shell]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[MultiLayer Wiper](https://attack.mitre.org/software/S1135) uses a batch script launched via a scheduled task to delete Windows Event Logs.(Citation: Unit42 Agrius 2023)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--a0004fa0-4650-4875-aa11-78aa3b34c7ea`.
