---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0040"
target_object: "T1566.002"
stix_relationship_id: "relationship--e35a6a79-0ffc-4835-aaf8-e42dd20a7e45"
---
# Relationship 8100: G0040 — uses → T1566.002

**Source object:** [[01 ATT&CK/G0040 - Patchwork|G0040: Patchwork]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1566.002 - Spearphishing Link|T1566.002: Spearphishing Link]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Patchwork](https://attack.mitre.org/groups/G0040) has used spearphishing with links to deliver files with exploits to initial victims.(Citation: Symantec Patchwork)(Citation: TrendMicro Patchwork Dec 2017)(Citation: Unit 42 BackConfig May 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e35a6a79-0ffc-4835-aaf8-e42dd20a7e45`.
