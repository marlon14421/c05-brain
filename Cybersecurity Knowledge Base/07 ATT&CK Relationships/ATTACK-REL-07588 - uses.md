---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0581"
target_object: "T1027.013"
stix_relationship_id: "relationship--e842c832-8e3a-487c-bdde-e1614fec6c7e"
---
# Relationship 7588: S0581 — uses → T1027.013

**Source object:** [[01 ATT&CK/S0581 - IronNetInjector|S0581: IronNetInjector]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1027.013 - Encrypted-Encoded File|T1027.013: Encrypted/Encoded File]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[IronNetInjector](https://attack.mitre.org/software/S0581) can obfuscate variable names, encrypt strings, as well as base64 encode and Rijndael encrypt payloads.(Citation: Unit 42 IronNetInjector February 2021 )

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e842c832-8e3a-487c-bdde-e1614fec6c7e`.
