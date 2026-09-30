---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1122"
target_object: "T1113"
stix_relationship_id: "relationship--2723c701-96d8-44e9-96ce-34c57e50a68e"
---
# Relationship 9570: S1122 — uses → T1113

**Source object:** [[01 ATT&CK/S1122 - Mispadu|S1122: Mispadu]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1113 - Screen Capture|T1113: Screen Capture]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Mispadu](https://attack.mitre.org/software/S1122) has the ability to capture screenshots on compromised hosts.(Citation: SCILabs Malteiro 2021)(Citation: SCILabs URSA/Mispadu Evolution 2023)(Citation: ESET Security Mispadu Facebook Ads 2019)(Citation: Metabase Q Mispadu Trojan 2023)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--2723c701-96d8-44e9-96ce-34c57e50a68e`.
