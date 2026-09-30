---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0240"
target_object: "T1115"
stix_relationship_id: "relationship--83f5442e-74c1-4e7b-83d8-9c254543bbac"
---
# Relationship 7153: S0240 — uses → T1115

**Source object:** [[01 ATT&CK/S0240 - ROKRAT|S0240: ROKRAT]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1115 - Clipboard Data|T1115: Clipboard Data]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[ROKRAT](https://attack.mitre.org/software/S0240) can extract clipboard data from a compromised host.(Citation: Volexity InkySquid RokRAT August 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--83f5442e-74c1-4e7b-83d8-9c254543bbac`.
