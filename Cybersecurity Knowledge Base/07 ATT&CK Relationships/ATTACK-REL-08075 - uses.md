---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0560"
target_object: "T1543.003"
stix_relationship_id: "relationship--9d70b17c-d3b7-43a2-9c35-d0b80bec2ec0"
---
# Relationship 8075: S0560 — uses → T1543.003

**Source object:** [[01 ATT&CK/S0560 - TEARDROP|S0560: TEARDROP]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1543.003 - Windows Service|T1543.003: Windows Service]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[TEARDROP](https://attack.mitre.org/software/S0560) ran as a Windows service from the c:\windows\syswow64 folder.(Citation: Check Point Sunburst Teardrop December 2020)(Citation: FireEye SUNBURST Backdoor December 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--9d70b17c-d3b7-43a2-9c35-d0b80bec2ec0`.
