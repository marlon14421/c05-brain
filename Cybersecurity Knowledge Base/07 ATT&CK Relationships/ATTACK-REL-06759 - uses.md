---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0156"
target_object: "T1082"
stix_relationship_id: "relationship--42dc03ec-03fb-4bf0-8f5f-e90d1aacd6e7"
---
# Relationship 6759: S0156 — uses → T1082

**Source object:** [[01 ATT&CK/S0156 - KOMPROGO|S0156: KOMPROGO]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1082 - System Information Discovery|T1082: System Information Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[KOMPROGO](https://attack.mitre.org/software/S0156) is capable of retrieving information about the infected system.(Citation: FireEye APT32 May 2017)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--42dc03ec-03fb-4bf0-8f5f-e90d1aacd6e7`.
