---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0350"
target_object: "T1021.001"
stix_relationship_id: "relationship--1d37f088-123f-41bb-9367-a1696dbfe895"
---
# Relationship 8694: S0350 — uses → T1021.001

**Source object:** [[01 ATT&CK/S0350 - zwShell|S0350: zwShell]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1021.001 - Remote Desktop Protocol|T1021.001: Remote Desktop Protocol]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[zwShell](https://attack.mitre.org/software/S0350) has used RDP for lateral movement.(Citation: McAfee Night Dragon)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--1d37f088-123f-41bb-9367-a1696dbfe895`.
