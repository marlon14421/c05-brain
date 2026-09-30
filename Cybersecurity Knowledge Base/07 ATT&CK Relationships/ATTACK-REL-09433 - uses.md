---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0646"
target_object: "T1204.001"
stix_relationship_id: "relationship--b5372961-d931-497e-8043-1bfa446f65d6"
---
# Relationship 9433: S0646 — uses → T1204.001

**Source object:** [[01 ATT&CK/S0646 - SpicyOmelette|S0646: SpicyOmelette]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1204.001 - Malicious Link|T1204.001: Malicious Link]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[SpicyOmelette](https://attack.mitre.org/software/S0646) has been executed through malicious links within spearphishing emails.(Citation: Secureworks GOLD KINGSWOOD September 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--b5372961-d931-497e-8043-1bfa446f65d6`.
