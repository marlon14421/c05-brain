---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0646"
target_object: "T1105"
stix_relationship_id: "relationship--7f7f05aa-a246-48ce-89d2-48035cac5ffa"
---
# Relationship 6538: S0646 — uses → T1105

**Source object:** [[01 ATT&CK/S0646 - SpicyOmelette|S0646: SpicyOmelette]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1105 - Ingress Tool Transfer|T1105: Ingress Tool Transfer]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[SpicyOmelette](https://attack.mitre.org/software/S0646) can download malicious files from threat actor controlled AWS URL's.(Citation: Secureworks GOLD KINGSWOOD September 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--7f7f05aa-a246-48ce-89d2-48035cac5ffa`.
