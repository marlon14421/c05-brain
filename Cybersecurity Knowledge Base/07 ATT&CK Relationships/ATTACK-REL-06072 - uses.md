---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0028"
target_object: "T1055"
stix_relationship_id: "relationship--edb47407-d848-4b72-abe6-9815aeaaaf37"
---
# Relationship 6072: C0028 — uses → T1055

**Source object:** [[01 ATT&CK/C0028 - 2015 Ukraine Electric Power Attack|C0028: 2015 Ukraine Electric Power Attack]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1055 - Process Injection|T1055: Process Injection]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

During the [2015 Ukraine Electric Power Attack](https://attack.mitre.org/campaigns/C0028), [Sandworm Team](https://attack.mitre.org/groups/G0034) loaded [BlackEnergy](https://attack.mitre.org/software/S0089) into svchost.exe, which then launched iexplore.exe for their C2. (Citation: Booz Allen Hamilton)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--edb47407-d848-4b72-abe6-9815aeaaaf37`.
