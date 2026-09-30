---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0202"
target_object: "T1059.003"
stix_relationship_id: "relationship--d9f924ec-aa93-48fd-aef6-2e545410f2d0"
---
# Relationship 7002: S0202 — uses → T1059.003

**Source object:** [[01 ATT&CK/S0202 - adbupd|S0202: adbupd]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059.003 - Windows Command Shell|T1059.003: Windows Command Shell]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[adbupd](https://attack.mitre.org/software/S0202) can run a copy of cmd.exe.(Citation: Microsoft PLATINUM April 2016)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--d9f924ec-aa93-48fd-aef6-2e545410f2d0`.
