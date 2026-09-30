---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0027"
target_object: "T1102"
stix_relationship_id: "relationship--08f2da07-4e03-46bd-a3d9-c79ef7dd9a45"
---
# Relationship 6830: C0027 — uses → T1102

**Source object:** [[01 ATT&CK/C0027 - C0027|C0027: C0027]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1102 - Web Service|T1102: Web Service]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

During [C0027](https://attack.mitre.org/campaigns/C0027), [Scattered Spider](https://attack.mitre.org/groups/G1015) downloaded tools from sites including file.io, GitHub, and paste.ee.(Citation: Crowdstrike TELCO BPO Campaign December 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--08f2da07-4e03-46bd-a3d9-c79ef7dd9a45`.
