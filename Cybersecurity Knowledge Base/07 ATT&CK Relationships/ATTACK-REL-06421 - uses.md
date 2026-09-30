---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0001"
target_object: "T1041"
stix_relationship_id: "relationship--cbc251b7-5541-408f-b11d-c57d600fc8cf"
---
# Relationship 6421: C0001 — uses → T1041

**Source object:** [[01 ATT&CK/C0001 - Frankenstein|C0001: Frankenstein]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1041 - Exfiltration Over C2 Channel|T1041: Exfiltration Over C2 Channel]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

During [Frankenstein](https://attack.mitre.org/campaigns/C0001), the threat actors collected information via [Empire](https://attack.mitre.org/software/S0363), which sent the data back to the adversary's C2.(Citation: Talos Frankenstein June 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--cbc251b7-5541-408f-b11d-c57d600fc8cf`.
