---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0030"
target_object: "T1560.001"
stix_relationship_id: "relationship--cc58b10e-0fb0-4ee3-95b6-ae2bbaedcdea"
---
# Relationship 7860: G0030 — uses → T1560.001

**Source object:** [[01 ATT&CK/G0030 - Lotus Blossom|G0030: Lotus Blossom]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1560.001 - Archive via Utility|T1560.001: Archive via Utility]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Lotus Blossom](https://attack.mitre.org/groups/G0030) has used WinRAR for compressing data in RAR format.(Citation: Cisco LotusBlossom 2025)(Citation: Symantec Bilbug 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--cc58b10e-0fb0-4ee3-95b6-ae2bbaedcdea`.
