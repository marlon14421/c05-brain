---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1169"
target_object: "T1041"
stix_relationship_id: "relationship--921181fc-7296-4d9d-9209-86d2094bf0bd"
---
# Relationship 7371: S1169 — uses → T1041

**Source object:** [[01 ATT&CK/S1169 - Mango|S1169: Mango]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1041 - Exfiltration Over C2 Channel|T1041: Exfiltration Over C2 Channel]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Mango](https://attack.mitre.org/software/S1169) can use its HTTP C2 channel for exfiltration.(Citation: ESET OilRig Campaigns Sep 2023)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--921181fc-7296-4d9d-9209-86d2094bf0bd`.
