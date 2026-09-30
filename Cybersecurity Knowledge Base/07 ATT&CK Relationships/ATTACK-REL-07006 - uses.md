---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0045"
target_object: "T1041"
stix_relationship_id: "relationship--d8abe157-f6cd-4959-b9d5-e0c87d16bcfe"
---
# Relationship 7006: S0045 — uses → T1041

**Source object:** [[01 ATT&CK/S0045 - ADVSTORESHELL|S0045: ADVSTORESHELL]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1041 - Exfiltration Over C2 Channel|T1041: Exfiltration Over C2 Channel]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[ADVSTORESHELL](https://attack.mitre.org/software/S0045) exfiltrates data over the same channel used for C2.(Citation: ESET Sednit Part 2)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--d8abe157-f6cd-4959-b9d5-e0c87d16bcfe`.
