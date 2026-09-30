---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0148"
target_object: "T1027.015"
stix_relationship_id: "relationship--349f297f-48bf-4105-b92c-960c56aaaacf"
---
# Relationship 6772: S0148 — uses → T1027.015

**Source object:** [[01 ATT&CK/S0148 - RTM|S0148: RTM]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1027.015 - Compression|T1027.015: Compression]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[RTM](https://attack.mitre.org/software/S0148) has been delivered to targets as various archive files including ZIP, 7-ZIP, and RAR.(Citation: ESET RTM Feb 2017)(Citation: Unit42 Redaman January 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--349f297f-48bf-4105-b92c-960c56aaaacf`.
