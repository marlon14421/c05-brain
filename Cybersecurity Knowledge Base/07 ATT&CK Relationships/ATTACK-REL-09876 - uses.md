---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0457"
target_object: "T1106"
stix_relationship_id: "relationship--aa045472-7c41-49c5-af44-4df9cf1fa073"
---
# Relationship 9876: S0457 — uses → T1106

**Source object:** [[01 ATT&CK/S0457 - Netwalker|S0457: Netwalker]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1106 - Native API|T1106: Native API]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Netwalker](https://attack.mitre.org/software/S0457) can use Windows API functions to inject the ransomware DLL.(Citation: TrendMicro Netwalker May 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--aa045472-7c41-49c5-af44-4df9cf1fa073`.
