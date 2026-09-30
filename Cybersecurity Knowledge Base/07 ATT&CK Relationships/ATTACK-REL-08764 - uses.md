---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0584"
target_object: "T1053.005"
stix_relationship_id: "relationship--ac85daf7-c5ee-4f53-8ed8-0049ac7cc6e9"
---
# Relationship 8764: S0584 — uses → T1053.005

**Source object:** [[01 ATT&CK/S0584 - AppleJeus|S0584: AppleJeus]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1053.005 - Scheduled Task|T1053.005: Scheduled Task]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[AppleJeus](https://attack.mitre.org/software/S0584) has created a scheduled SYSTEM task that runs when a user logs in.(Citation: CISA AppleJeus Feb 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--ac85daf7-c5ee-4f53-8ed8-0049ac7cc6e9`.
