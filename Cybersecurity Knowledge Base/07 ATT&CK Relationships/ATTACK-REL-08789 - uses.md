---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0028"
target_object: "T1056.001"
stix_relationship_id: "relationship--d2aa3c9f-0f1f-49ff-81ef-94e229f7c6e2"
---
# Relationship 8789: C0028 — uses → T1056.001

**Source object:** [[01 ATT&CK/C0028 - 2015 Ukraine Electric Power Attack|C0028: 2015 Ukraine Electric Power Attack]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1056.001 - Keylogging|T1056.001: Keylogging]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

During the [2015 Ukraine Electric Power Attack](https://attack.mitre.org/campaigns/C0028), [Sandworm Team](https://attack.mitre.org/groups/G0034) gathered account credentials via a [BlackEnergy](https://attack.mitre.org/software/S0089) keylogger plugin. (Citation: Booz Allen Hamilton)(Citation: Ukraine15 - EISAC - 201603)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--d2aa3c9f-0f1f-49ff-81ef-94e229f7c6e2`.
