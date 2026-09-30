---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0030"
target_object: "S0590"
stix_relationship_id: "relationship--a20e2809-ec0d-4378-8ee2-0691b651236c"
---
# Relationship 6381: G0030 — uses → S0590

**Source object:** [[01 ATT&CK/G0030 - Lotus Blossom|G0030: Lotus Blossom]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/S0590 - NBTscan|S0590: NBTscan]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Lotus Blossom](https://attack.mitre.org/groups/G0030) has used [NBTscan](https://attack.mitre.org/software/S0590) during operations.(Citation: Symantec Bilbug 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--a20e2809-ec0d-4378-8ee2-0691b651236c`.
