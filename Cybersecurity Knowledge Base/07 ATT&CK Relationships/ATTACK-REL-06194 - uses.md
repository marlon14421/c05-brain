---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0434"
target_object: "T1140"
stix_relationship_id: "relationship--239cb026-369a-43f0-922c-cdc38d124430"
---
# Relationship 6194: S0434 — uses → T1140

**Source object:** [[01 ATT&CK/S0434 - Imminent Monitor|S0434: Imminent Monitor]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1140 - Deobfuscate-Decode Files or Information|T1140: Deobfuscate/Decode Files or Information]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Imminent Monitor](https://attack.mitre.org/software/S0434) has decoded malware components that are then dropped to the system.(Citation: QiAnXin APT-C-36 Feb2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--239cb026-369a-43f0-922c-cdc38d124430`.
