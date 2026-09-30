---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1242"
target_object: "T1134"
stix_relationship_id: "relationship--0a068599-574d-4df3-8b05-6194e7366cc4"
---
# Relationship 8571: S1242 — uses → T1134

**Source object:** [[01 ATT&CK/S1242 - Qilin|S1242: Qilin]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1134 - Access Token Manipulation|T1134: Access Token Manipulation]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Qilin](https://attack.mitre.org/software/S1242) can use an embedded [Mimikatz](https://attack.mitre.org/software/S0002) module for token manipulation.(Citation: Picus Qilin MAR 2025)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--0a068599-574d-4df3-8b05-6194e7366cc4`.
