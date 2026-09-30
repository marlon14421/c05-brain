---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0145"
target_object: "T1105"
stix_relationship_id: "relationship--d04d6101-f6f6-42a2-8679-351956b75228"
---
# Relationship 5320: S0145 — uses → T1105

**Source object:** [[01 ATT&CK/S0145 - POWERSOURCE|S0145: POWERSOURCE]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1105 - Ingress Tool Transfer|T1105: Ingress Tool Transfer]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[POWERSOURCE](https://attack.mitre.org/software/S0145) has been observed being used to download [TEXTMATE](https://attack.mitre.org/software/S0146) and the Cobalt Strike Beacon payload onto victims.(Citation: FireEye FIN7 March 2017)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--d04d6101-f6f6-42a2-8679-351956b75228`.
