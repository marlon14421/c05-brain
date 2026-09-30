---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0045"
target_object: "T1074.002"
stix_relationship_id: "relationship--9ffd6752-5d0f-4108-8cab-8541b54c0434"
---
# Relationship 6216: G0045 — uses → T1074.002

**Source object:** [[01 ATT&CK/G0045 - menuPass|G0045: menuPass]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1074.002 - Remote Data Staging|T1074.002: Remote Data Staging]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[menuPass](https://attack.mitre.org/groups/G0045) has staged data on remote MSP systems or other victim networks prior to exfiltration.(Citation: PWC Cloud Hopper April 2017)(Citation: Symantec Cicada November 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--9ffd6752-5d0f-4108-8cab-8541b54c0434`.
