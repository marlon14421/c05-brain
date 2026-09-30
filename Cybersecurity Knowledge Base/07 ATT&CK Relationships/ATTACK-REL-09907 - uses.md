---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1099"
target_object: "T1106"
stix_relationship_id: "relationship--fcacc3e1-f343-4013-97cf-ce5d5f700c13"
---
# Relationship 9907: S1099 — uses → T1106

**Source object:** [[01 ATT&CK/S1099 - Samurai|S1099: Samurai]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1106 - Native API|T1106: Native API]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Samurai](https://attack.mitre.org/software/S1099) has the ability to call Windows APIs.(Citation: Kaspersky ToddyCat June 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--fcacc3e1-f343-4013-97cf-ce5d5f700c13`.
