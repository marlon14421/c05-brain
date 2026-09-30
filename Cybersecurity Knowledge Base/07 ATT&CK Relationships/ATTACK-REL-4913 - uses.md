---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0172"
target_object: "T1012"
stix_relationship_id: "relationship--f44478f1-fdd7-4e84-8b96-60e6c6a10683"
---
# Relationship 4913: S0172 — uses → T1012

**Source object:** [[01 ATT&CK/S0172 - Reaver|S0172: Reaver]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1012 - Query Registry|T1012: Query Registry]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Reaver](https://attack.mitre.org/software/S0172) queries the Registry to determine the correct Startup path to use for persistence.(Citation: Palo Alto Reaver Nov 2017)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--f44478f1-fdd7-4e84-8b96-60e6c6a10683`.
