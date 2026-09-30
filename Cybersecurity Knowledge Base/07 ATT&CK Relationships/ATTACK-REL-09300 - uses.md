---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0698"
target_object: "T1569.002"
stix_relationship_id: "relationship--29c9b21f-7ea0-48f0-bd90-978d4f37813f"
---
# Relationship 9300: S0698 — uses → T1569.002

**Source object:** [[01 ATT&CK/S0698 - HermeticWizard|S0698: HermeticWizard]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1569.002 - Service Execution|T1569.002: Service Execution]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[HermeticWizard](https://attack.mitre.org/software/S0698) can use `OpenRemoteServiceManager` to create a service.(Citation: ESET Hermetic Wizard March 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--29c9b21f-7ea0-48f0-bd90-978d4f37813f`.
