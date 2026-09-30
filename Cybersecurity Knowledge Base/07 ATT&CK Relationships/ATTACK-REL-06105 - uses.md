---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0127"
target_object: "T1027.003"
stix_relationship_id: "relationship--59ef906c-f395-427a-9cd5-30887a983516"
---
# Relationship 6105: G0127 — uses → T1027.003

**Source object:** [[01 ATT&CK/G0127 - TA551|G0127: TA551]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1027.003 - Steganography|T1027.003: Steganography]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[TA551](https://attack.mitre.org/groups/G0127) has hidden encoded data for malware DLLs in a PNG.(Citation: Unit 42 TA551 Jan 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--59ef906c-f395-427a-9cd5-30887a983516`.
