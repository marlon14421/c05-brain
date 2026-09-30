---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1046"
target_object: "T1140"
stix_relationship_id: "relationship--c935af5a-b6e3-41b8-afa8-f9d7ad593201"
---
# Relationship 5964: S1046 — uses → T1140

**Source object:** [[01 ATT&CK/S1046 - PowGoop|S1046: PowGoop]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1140 - Deobfuscate-Decode Files or Information|T1140: Deobfuscate/Decode Files or Information]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[PowGoop](https://attack.mitre.org/software/S1046) can decrypt PowerShell scripts for execution.(Citation: DHS CISA AA22-055A MuddyWater February 2022)(Citation: CYBERCOM Iranian Intel Cyber January 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c935af5a-b6e3-41b8-afa8-f9d7ad593201`.
