---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0526"
target_object: "T1140"
stix_relationship_id: "relationship--f2cb5393-d33f-4ee3-a2c0-197c1e032ea5"
---
# Relationship 8832: S0526 — uses → T1140

**Source object:** [[01 ATT&CK/S0526 - KGH_SPY|S0526: KGH_SPY]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1140 - Deobfuscate-Decode Files or Information|T1140: Deobfuscate/Decode Files or Information]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[KGH_SPY](https://attack.mitre.org/software/S0526) can decrypt encrypted strings and write them to a newly created folder.(Citation: Cybereason Kimsuky November 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--f2cb5393-d33f-4ee3-a2c0-197c1e032ea5`.
