---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0280"
target_object: "T1140"
stix_relationship_id: "relationship--f16f0b46-3363-48bd-9a13-c8751fdedf1c"
---
# Relationship 9379: S0280 — uses → T1140

**Source object:** [[01 ATT&CK/S0280 - MirageFox|S0280: MirageFox]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1140 - Deobfuscate-Decode Files or Information|T1140: Deobfuscate/Decode Files or Information]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[MirageFox](https://attack.mitre.org/software/S0280) has a function for decrypting data containing C2 configuration information.(Citation: APT15 Intezer June 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--f16f0b46-3363-48bd-9a13-c8751fdedf1c`.
