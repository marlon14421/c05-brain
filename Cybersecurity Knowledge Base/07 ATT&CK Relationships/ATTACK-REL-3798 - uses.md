---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0461"
target_object: "T1016"
stix_relationship_id: "relationship--9c15fad4-3614-4bf0-90db-84749f34f91c"
---
# Relationship 3798: S0461 — uses → T1016

**Source object:** [[01 ATT&CK/S0461 - SDBbot|S0461: SDBbot]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1016 - System Network Configuration Discovery|T1016: System Network Configuration Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[SDBbot](https://attack.mitre.org/software/S0461) has the ability to determine the domain name and whether a proxy is configured on a compromised host.(Citation: Proofpoint TA505 October 2019)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--9c15fad4-3614-4bf0-90db-84749f34f91c`.
