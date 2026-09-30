---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0689"
target_object: "T1059.001"
stix_relationship_id: "relationship--375253bd-1832-4177-a1b1-92b42a6a599b"
---
# Relationship 5997: S0689 — uses → T1059.001

**Source object:** [[01 ATT&CK/S0689 - WhisperGate|S0689: WhisperGate]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059.001 - PowerShell|T1059.001: PowerShell]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[WhisperGate](https://attack.mitre.org/software/S0689) can use PowerShell to support multiple actions including execution and defense evasion.(Citation: Unit 42 WhisperGate January 2022)(Citation: Cisco Ukraine Wipers January 2022)(Citation: Medium S2W WhisperGate January 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--375253bd-1832-4177-a1b1-92b42a6a599b`.
