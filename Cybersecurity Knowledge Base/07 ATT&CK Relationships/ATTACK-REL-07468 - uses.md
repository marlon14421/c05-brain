---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0140"
target_object: "T1486"
stix_relationship_id: "relationship--d7f4f6eb-05b8-43af-8d8a-e06b1d950165"
---
# Relationship 7468: S0140 — uses → T1486

**Source object:** [[01 ATT&CK/S0140 - Shamoon|S0140: Shamoon]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1486 - Data Encrypted for Impact|T1486: Data Encrypted for Impact]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Shamoon](https://attack.mitre.org/software/S0140) has an operational mode for encrypting data instead of overwriting it.(Citation: Palo Alto Shamoon Nov 2016)(Citation: Unit 42 Shamoon3 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--d7f4f6eb-05b8-43af-8d8a-e06b1d950165`.
