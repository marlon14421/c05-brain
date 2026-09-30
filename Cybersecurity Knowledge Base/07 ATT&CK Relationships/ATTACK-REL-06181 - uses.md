---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0080"
target_object: "T1046"
stix_relationship_id: "relationship--edcd7a59-f8e0-41e5-b0f5-8d348fa13a10"
---
# Relationship 6181: G0080 — uses → T1046

**Source object:** [[01 ATT&CK/G0080 - Cobalt Group|G0080: Cobalt Group]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1046 - Network Service Discovery|T1046: Network Service Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Cobalt Group](https://attack.mitre.org/groups/G0080) leveraged an open-source tool called SoftPerfect Network Scanner to perform network scanning.(Citation: PTSecurity Cobalt Group Aug 2017)(Citation: PTSecurity Cobalt Dec 2016)(Citation: Group IB Cobalt Aug 2017)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--edcd7a59-f8e0-41e5-b0f5-8d348fa13a10`.
