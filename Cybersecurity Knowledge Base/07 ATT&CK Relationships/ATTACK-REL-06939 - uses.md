---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0649"
target_object: "T1041"
stix_relationship_id: "relationship--9e26a79d-1982-46b8-b077-0bb6ca30cd3b"
---
# Relationship 6939: S0649 — uses → T1041

**Source object:** [[01 ATT&CK/S0649 - SMOKEDHAM|S0649: SMOKEDHAM]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1041 - Exfiltration Over C2 Channel|T1041: Exfiltration Over C2 Channel]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[SMOKEDHAM](https://attack.mitre.org/software/S0649) has exfiltrated data to its C2 server.(Citation: FireEye SMOKEDHAM June 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--9e26a79d-1982-46b8-b077-0bb6ca30cd3b`.
