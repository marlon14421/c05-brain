---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1150"
target_object: "T1140"
stix_relationship_id: "relationship--708ac02f-8419-43bd-a6d6-682e28faa507"
---
# Relationship 7095: S1150 — uses → T1140

**Source object:** [[01 ATT&CK/S1150 - ROADSWEEP|S1150: ROADSWEEP]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1140 - Deobfuscate-Decode Files or Information|T1140: Deobfuscate/Decode Files or Information]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[ROADSWEEP](https://attack.mitre.org/software/S1150) can decrypt embedded scripts prior to execution.(Citation: Mandiant ROADSWEEP August 2022)(Citation: CISA Iran Albanian Attacks September 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--708ac02f-8419-43bd-a6d6-682e28faa507`.
