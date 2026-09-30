---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0517"
target_object: "T1112"
stix_relationship_id: "relationship--332ce4cd-311a-457f-ae10-6d8e3ef7bc77"
---
# Relationship 8960: S0517 — uses → T1112

**Source object:** [[01 ATT&CK/S0517 - Pillowmint|S0517: Pillowmint]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1112 - Modify Registry|T1112: Modify Registry]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Pillowmint](https://attack.mitre.org/software/S0517) has modified the Registry key HKLM\SOFTWARE\Microsoft\DRM to store a malicious payload.(Citation: Trustwave Pillowmint June 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--332ce4cd-311a-457f-ae10-6d8e3ef7bc77`.
