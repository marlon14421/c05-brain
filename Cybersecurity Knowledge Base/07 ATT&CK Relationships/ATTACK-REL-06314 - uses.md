---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0632"
target_object: "T1140"
stix_relationship_id: "relationship--c9256d21-a464-477a-8756-96eae300b0e4"
---
# Relationship 6314: S0632 — uses → T1140

**Source object:** [[01 ATT&CK/S0632 - GrimAgent|S0632: GrimAgent]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1140 - Deobfuscate-Decode Files or Information|T1140: Deobfuscate/Decode Files or Information]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[GrimAgent](https://attack.mitre.org/software/S0632) can use a decryption algorithm for strings based on Rotate on Right (RoR) and Rotate on Left (RoL) functionality.(Citation: Group IB GrimAgent July 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c9256d21-a464-477a-8756-96eae300b0e4`.
