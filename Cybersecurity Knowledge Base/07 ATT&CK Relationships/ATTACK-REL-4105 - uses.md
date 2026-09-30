---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S9001"
target_object: "T1071.004"
stix_relationship_id: "relationship--5fac7323-462e-4ef5-848b-5ff54833a67e"
---
# Relationship 4105: S9001 — uses → T1071.004

**Source object:** [[01 ATT&CK/S9001 - SystemBC|S9001: SystemBC]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1071.004 - DNS|T1071.004: DNS]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[SystemBC](https://attack.mitre.org/software/S9001) has used DNS servers to resolve .bit domains to C2 infrastructure.(Citation: HarmonProofpoint_SystemBC_Aug2019)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--5fac7323-462e-4ef5-848b-5ff54833a67e`.
