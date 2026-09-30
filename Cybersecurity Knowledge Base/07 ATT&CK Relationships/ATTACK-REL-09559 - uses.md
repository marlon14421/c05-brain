---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0262"
target_object: "T1056.001"
stix_relationship_id: "relationship--2ede8fe4-0a44-4c31-ba4c-d3282d57b4b8"
---
# Relationship 9559: S0262 — uses → T1056.001

**Source object:** [[01 ATT&CK/S0262 - QuasarRAT|S0262: QuasarRAT]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1056.001 - Keylogging|T1056.001: Keylogging]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[QuasarRAT](https://attack.mitre.org/software/S0262) has a built-in keylogger.(Citation: GitHub QuasarRAT)(Citation: Volexity Patchwork June 2018)(Citation: Kaspersky BlindEagle AUG 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--2ede8fe4-0a44-4c31-ba4c-d3282d57b4b8`.
