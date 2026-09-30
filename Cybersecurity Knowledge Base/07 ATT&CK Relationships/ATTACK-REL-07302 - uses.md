---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0094"
target_object: "T1684.001"
stix_relationship_id: "relationship--21f3796d-3dd7-4b43-bd80-ec75ef3edfef"
---
# Relationship 7302: G0094 — uses → T1684.001

**Source object:** [[01 ATT&CK/G0094 - Kimsuky|G0094: Kimsuky]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1684.001 - Impersonation|T1684.001: Impersonation]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Kimsuky](https://attack.mitre.org/groups/G0094) has also impersonated legitimate people, such as a foreign advisor, an embassy employee, and a think tank employee.(Citation: FBI_KimsukyQR_Jan2026) [Kimsuky](https://attack.mitre.org/groups/G0094) has also purported to be a Japanese diplomat to communicate with the victims.(Citation: NaumaanProofpoint_GlobalClickFix_April2025)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--21f3796d-3dd7-4b43-bd80-ec75ef3edfef`.
