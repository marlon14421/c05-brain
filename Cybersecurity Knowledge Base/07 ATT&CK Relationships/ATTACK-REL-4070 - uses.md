---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0140"
target_object: "T1561.002"
stix_relationship_id: "relationship--10bc4c79-d47f-4d49-bc06-c65ae376a4b6"
---
# Relationship 4070: S0140 — uses → T1561.002

**Source object:** [[01 ATT&CK/S0140 - Shamoon|S0140: Shamoon]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1561.002 - Disk Structure Wipe|T1561.002: Disk Structure Wipe]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Shamoon](https://attack.mitre.org/software/S0140) has been seen overwriting features of disk structure such as the MBR.(Citation: Symantec Shamoon 2012)(Citation: FireEye Shamoon Nov 2016)(Citation: Palo Alto Shamoon Nov 2016)(Citation: Unit 42 Shamoon3 2018)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--10bc4c79-d47f-4d49-bc06-c65ae376a4b6`.
