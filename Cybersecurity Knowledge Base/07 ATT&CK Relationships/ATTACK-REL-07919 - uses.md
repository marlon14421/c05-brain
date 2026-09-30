---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0462"
target_object: "T1027.010"
stix_relationship_id: "relationship--856aff2c-9289-4c45-ade7-24cb3c338003"
---
# Relationship 7919: S0462 — uses → T1027.010

**Source object:** [[01 ATT&CK/S0462 - CARROTBAT|S0462: CARROTBAT]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1027.010 - Command Obfuscation|T1027.010: Command Obfuscation]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[CARROTBAT](https://attack.mitre.org/software/S0462) has the ability to execute obfuscated commands on the infected host.(Citation: Unit 42 CARROTBAT November 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--856aff2c-9289-4c45-ade7-24cb3c338003`.
