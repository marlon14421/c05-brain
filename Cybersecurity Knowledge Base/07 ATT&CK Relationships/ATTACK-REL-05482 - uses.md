---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0021"
target_object: "T1056.001"
stix_relationship_id: "relationship--062874d1-8ca9-400f-8367-670b9c7c3280"
---
# Relationship 5482: S0021 — uses → T1056.001

**Source object:** [[01 ATT&CK/S0021 - Derusbi|S0021: Derusbi]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1056.001 - Keylogging|T1056.001: Keylogging]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Derusbi](https://attack.mitre.org/software/S0021) is capable of logging keystrokes.(Citation: FireEye Periscope March 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--062874d1-8ca9-400f-8367-670b9c7c3280`.
