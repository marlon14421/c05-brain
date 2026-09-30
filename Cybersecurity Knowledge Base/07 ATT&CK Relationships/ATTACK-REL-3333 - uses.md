---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0481"
target_object: "T1569.002"
stix_relationship_id: "relationship--347de212-26bf-4ad4-963f-c4dfa3c821d1"
---
# Relationship 3333: S0481 — uses → T1569.002

**Source object:** [[01 ATT&CK/S0481 - Ragnar Locker|S0481: Ragnar Locker]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1569.002 - Service Execution|T1569.002: Service Execution]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Ragnar Locker](https://attack.mitre.org/software/S0481) has used sc.exe to execute a service that it creates.(Citation: Sophos Ragnar May 2020)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--347de212-26bf-4ad4-963f-c4dfa3c821d1`.
