---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0491"
target_object: "T1569.002"
stix_relationship_id: "relationship--e7b10c00-0860-4592-a72c-e14e993e972b"
---
# Relationship 3219: S0491 — uses → T1569.002

**Source object:** [[01 ATT&CK/S0491 - StrongPity|S0491: StrongPity]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1569.002 - Service Execution|T1569.002: Service Execution]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[StrongPity](https://attack.mitre.org/software/S0491) can install a service to execute itself as a service.(Citation: Talos Promethium June 2020)(Citation: Bitdefender StrongPity June 2020)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e7b10c00-0860-4592-a72c-e14e993e972b`.
