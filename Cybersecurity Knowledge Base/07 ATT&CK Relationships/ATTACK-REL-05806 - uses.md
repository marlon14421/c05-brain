---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0673"
target_object: "T1120"
stix_relationship_id: "relationship--ff2f9b25-f36a-4031-8013-1e746cc40948"
---
# Relationship 5806: S0673 — uses → T1120

**Source object:** [[01 ATT&CK/S0673 - DarkWatchman|S0673: DarkWatchman]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1120 - Peripheral Device Discovery|T1120: Peripheral Device Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[DarkWatchman](https://attack.mitre.org/software/S0673) can list signed PnP drivers for smartcard readers.(Citation: Prevailion DarkWatchman 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--ff2f9b25-f36a-4031-8013-1e746cc40948`.
