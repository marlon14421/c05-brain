---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S9018"
target_object: "T1140"
stix_relationship_id: "relationship--609f941d-2768-4e1f-9286-774a954a8bdb"
---
# Relationship 8000: S9018 — uses → T1140

**Source object:** [[01 ATT&CK/S9018 - HeartCrypt|S9018: HeartCrypt]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1140 - Deobfuscate-Decode Files or Information|T1140: Deobfuscate/Decode Files or Information]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[HeartCrypt](https://attack.mitre.org/software/S9018) can decrypt payloads prior to execution.(Citation: Palo Alto HeartCrypt DEC 2024)(Citation: Check Point Blind Eagle MAR 2025)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--609f941d-2768-4e1f-9286-774a954a8bdb`.
