---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1048"
target_object: "T1070.007"
stix_relationship_id: "relationship--4e8250fb-25d8-4a9a-ba49-40d7c4090c64"
---
# Relationship 3143: G1048 — uses → T1070.007

**Source object:** [[01 ATT&CK/G1048 - UNC3886|G1048: UNC3886]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1070.007 - Clear Network Connection History and Configurations|T1070.007: Clear Network Connection History and Configurations]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[UNC3886](https://attack.mitre.org/groups/G1048) has cleared specific events that contained the threat actor’s IP address from multiple log sources.(Citation: Mandiant Fortinet Zero Day)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--4e8250fb-25d8-4a9a-ba49-40d7c4090c64`.
