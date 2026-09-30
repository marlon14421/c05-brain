---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0125"
target_object: "T1016.001"
stix_relationship_id: "relationship--baaa6228-daa9-45e9-884e-42add3851843"
---
# Relationship 3668: G0125 — uses → T1016.001

**Source object:** [[01 ATT&CK/G0125 - HAFNIUM|G0125: HAFNIUM]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1016.001 - Internet Connection Discovery|T1016.001: Internet Connection Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[HAFNIUM](https://attack.mitre.org/groups/G0125) has checked for network connectivity from a compromised host using `ping`, including attempts to contact `google[.]com`.(Citation: Rapid7 HAFNIUM Mar 2021)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--baaa6228-daa9-45e9-884e-42add3851843`.
