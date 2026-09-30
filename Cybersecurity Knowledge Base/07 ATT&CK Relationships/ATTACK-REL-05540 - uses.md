---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1130"
target_object: "T1497"
stix_relationship_id: "relationship--421b0dc2-fc78-4eb3-a336-ce8e4febccef"
---
# Relationship 5540: S1130 — uses → T1497

**Source object:** [[01 ATT&CK/S1130 - Raspberry Robin|S1130: Raspberry Robin]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1497 - Virtualization-Sandbox Evasion|T1497: Virtualization/Sandbox Evasion]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Raspberry Robin](https://attack.mitre.org/software/S1130) contains real and fake second-stage payloads following initial execution, with the real payload only delivered if the malware determines it is not running in a virtualized environment.(Citation: TrendMicro RaspberryRobin 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--421b0dc2-fc78-4eb3-a336-ce8e4febccef`.
