---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0646"
target_object: "T1059.007"
stix_relationship_id: "relationship--ab55f99b-5239-4aea-93f7-e1002520bf05"
---
# Relationship 7134: S0646 — uses → T1059.007

**Source object:** [[01 ATT&CK/S0646 - SpicyOmelette|S0646: SpicyOmelette]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059.007 - JavaScript|T1059.007: JavaScript]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[SpicyOmelette](https://attack.mitre.org/software/S0646) has the ability to execute arbitrary JavaScript code on a compromised host.(Citation: Secureworks GOLD KINGSWOOD September 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--ab55f99b-5239-4aea-93f7-e1002520bf05`.
