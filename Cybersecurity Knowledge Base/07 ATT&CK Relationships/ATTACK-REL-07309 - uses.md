---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0228"
target_object: "T1685"
stix_relationship_id: "relationship--38bde25a-6e15-4c7a-91e6-4758d113049b"
---
# Relationship 7309: S0228 — uses → T1685

**Source object:** [[01 ATT&CK/S0228 - NanHaiShu|S0228: NanHaiShu]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1685 - Disable or Modify Tools|T1685: Disable or Modify Tools]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[NanHaiShu](https://attack.mitre.org/software/S0228) can change Internet Explorer settings to reduce warnings about malware activity.(Citation: Proofpoint Leviathan Oct 2017)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--38bde25a-6e15-4c7a-91e6-4758d113049b`.
