---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0040"
target_object: "T1059.003"
stix_relationship_id: "relationship--c5da001c-2c17-4e83-8e5c-21863ead4bd9"
---
# Relationship 6284: G0040 — uses → T1059.003

**Source object:** [[01 ATT&CK/G0040 - Patchwork|G0040: Patchwork]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059.003 - Windows Command Shell|T1059.003: Windows Command Shell]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Patchwork](https://attack.mitre.org/groups/G0040) ran a reverse shell with Meterpreter.(Citation: Cymmetria Patchwork) [Patchwork](https://attack.mitre.org/groups/G0040) used JavaScript code and .SCT files on victim machines.(Citation: TrendMicro Patchwork Dec 2017)(Citation: Volexity Patchwork June 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c5da001c-2c17-4e83-8e5c-21863ead4bd9`.
