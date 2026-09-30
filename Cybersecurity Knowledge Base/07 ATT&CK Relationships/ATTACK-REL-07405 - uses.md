---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0449"
target_object: "T1055.001"
stix_relationship_id: "relationship--44fab50d-4fb6-4a8a-ab7a-84dcb70443f5"
---
# Relationship 7405: S0449 — uses → T1055.001

**Source object:** [[01 ATT&CK/S0449 - Maze|S0449: Maze]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1055.001 - Dynamic-link Library Injection|T1055.001: Dynamic-link Library Injection]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Maze](https://attack.mitre.org/software/S0449) has injected the malware DLL into a target process.(Citation: McAfee Maze March 2020)(Citation: Sophos Maze VM September 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--44fab50d-4fb6-4a8a-ab7a-84dcb70443f5`.
