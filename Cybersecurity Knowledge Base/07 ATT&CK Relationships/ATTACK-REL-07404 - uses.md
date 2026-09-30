---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0398"
target_object: "T1569.002"
stix_relationship_id: "relationship--737788fa-f921-4147-9148-c39228f76e85"
---
# Relationship 7404: S0398 — uses → T1569.002

**Source object:** [[01 ATT&CK/S0398 - HyperBro|S0398: HyperBro]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1569.002 - Service Execution|T1569.002: Service Execution]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[HyperBro](https://attack.mitre.org/software/S0398) has the ability to start and stop a specified service.(Citation: Unit42 Emissary Panda May 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--737788fa-f921-4147-9148-c39228f76e85`.
