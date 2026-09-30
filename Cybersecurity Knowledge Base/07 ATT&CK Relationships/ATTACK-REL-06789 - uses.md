---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0381"
target_object: "T1041"
stix_relationship_id: "relationship--9b77175f-5bf4-4f4e-a064-55d88babf1fe"
---
# Relationship 6789: S0381 — uses → T1041

**Source object:** [[01 ATT&CK/S0381 - FlawedAmmyy|S0381: FlawedAmmyy]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1041 - Exfiltration Over C2 Channel|T1041: Exfiltration Over C2 Channel]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[FlawedAmmyy](https://attack.mitre.org/software/S0381) has sent data collected from a compromised host to its C2 servers.(Citation: Korean FSI TA505 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--9b77175f-5bf4-4f4e-a064-55d88babf1fe`.
