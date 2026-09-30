---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0178"
target_object: "T1036.004"
stix_relationship_id: "relationship--84bc4ba8-ab0e-4c60-92ed-26496a831611"
---
# Relationship 6885: S0178 — uses → T1036.004

**Source object:** [[01 ATT&CK/S0178 - Truvasys|S0178: Truvasys]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1036.004 - Masquerade Task or Service|T1036.004: Masquerade Task or Service]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

To establish persistence, [Truvasys](https://attack.mitre.org/software/S0178) adds a Registry Run key with a value "TaskMgr" in an attempt to masquerade as the legitimate Windows Task Manager.(Citation: Microsoft Win Defender Truvasys Sep 2017)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--84bc4ba8-ab0e-4c60-92ed-26496a831611`.
