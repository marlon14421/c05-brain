---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1221"
target_object: "T1140"
stix_relationship_id: "relationship--6b66277b-be7b-484b-86f4-fd97c7a4d4b7"
---
# Relationship 9460: S1221 — uses → T1140

**Source object:** [[01 ATT&CK/S1221 - MOPSLED|S1221: MOPSLED]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1140 - Deobfuscate-Decode Files or Information|T1140: Deobfuscate/Decode Files or Information]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[MOPSLED](https://attack.mitre.org/software/S1221) can decrypt obfuscated configuration files.(Citation: Google Cloud Mandiant UNC3886 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--6b66277b-be7b-484b-86f4-fd97c7a4d4b7`.
