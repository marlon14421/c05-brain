---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0365"
target_object: "T1529"
stix_relationship_id: "relationship--4932951a-b313-4024-bbad-434de3b747c5"
---
# Relationship 9278: S0365 — uses → T1529

**Source object:** [[01 ATT&CK/S0365 - Olympic Destroyer|S0365: Olympic Destroyer]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1529 - System Shutdown-Reboot|T1529: System Shutdown/Reboot]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Olympic Destroyer](https://attack.mitre.org/software/S0365) will shut down the compromised system after it is done modifying system configuration settings.(Citation: Talos Olympic Destroyer 2018)(Citation: US District Court Indictment GRU Unit 74455 October 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--4932951a-b313-4024-bbad-434de3b747c5`.
