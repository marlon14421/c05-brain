---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0007"
target_object: "T1014"
stix_relationship_id: "relationship--a5022441-bc5e-4b19-a773-b96b2719d1bb"
---
# Relationship 6193: G0007 — uses → T1014

**Source object:** [[01 ATT&CK/G0007 - APT28|G0007: APT28]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1014 - Rootkit|T1014: Rootkit]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[APT28](https://attack.mitre.org/groups/G0007) has used a UEFI (Unified Extensible Firmware Interface) rootkit known as [LoJax](https://attack.mitre.org/software/S0397).(Citation: Symantec APT28 Oct 2018)(Citation: ESET LoJax Sept 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--a5022441-bc5e-4b19-a773-b96b2719d1bb`.
