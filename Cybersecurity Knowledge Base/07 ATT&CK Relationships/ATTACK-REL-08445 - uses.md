---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0430"
target_object: "T1140"
stix_relationship_id: "relationship--45e9de66-7203-48e9-bd9b-096c289f35db"
---
# Relationship 8445: S0430 — uses → T1140

**Source object:** [[01 ATT&CK/S0430 - Winnti for Linux|S0430: Winnti for Linux]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1140 - Deobfuscate-Decode Files or Information|T1140: Deobfuscate/Decode Files or Information]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Winnti for Linux](https://attack.mitre.org/software/S0430) has decoded XOR encoded strings holding its configuration upon execution.(Citation: Chronicle Winnti for Linux May 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--45e9de66-7203-48e9-bd9b-096c289f35db`.
