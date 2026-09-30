---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1223"
target_object: "T1140"
stix_relationship_id: "relationship--a2644706-c75e-47b9-8167-f9db9481262e"
---
# Relationship 6090: S1223 — uses → T1140

**Source object:** [[01 ATT&CK/S1223 - THINCRUST|S1223: THINCRUST]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1140 - Deobfuscate-Decode Files or Information|T1140: Deobfuscate/Decode Files or Information]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[THINCRUST](https://attack.mitre.org/software/S1223) can deobfuscate RSA encrypted C2 commands received through the DEVICEID cookie.(Citation: Mandiant Fortinet Zero Day)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--a2644706-c75e-47b9-8167-f9db9481262e`.
