---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0526"
target_object: "T1041"
stix_relationship_id: "relationship--bb72c8e4-4d1b-47c6-ad2d-a345826b5645"
---
# Relationship 6121: S0526 — uses → T1041

**Source object:** [[01 ATT&CK/S0526 - KGH_SPY|S0526: KGH_SPY]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1041 - Exfiltration Over C2 Channel|T1041: Exfiltration Over C2 Channel]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[KGH_SPY](https://attack.mitre.org/software/S0526) can exfiltrate collected information from the host to the C2 server.(Citation: Cybereason Kimsuky November 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--bb72c8e4-4d1b-47c6-ad2d-a345826b5645`.
