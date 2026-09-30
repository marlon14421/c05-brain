---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S9016"
target_object: "T1140"
stix_relationship_id: "relationship--1f12b17d-366e-44b6-bc1b-cfbb2b305616"
---
# Relationship 6083: S9016 — uses → T1140

**Source object:** [[01 ATT&CK/S9016 - Caminho|S9016: Caminho]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1140 - Deobfuscate-Decode Files or Information|T1140: Deobfuscate/Decode Files or Information]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Caminho](https://attack.mitre.org/software/S9016) can deobfuscate downloaded files prior to execution.(Citation: Zscaler BlindEagle DEC 2025)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--1f12b17d-366e-44b6-bc1b-cfbb2b305616`.
