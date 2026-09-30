---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0090"
target_object: "T1056.001"
stix_relationship_id: "relationship--f4480854-9424-49d5-8b54-f839302e3ee7"
---
# Relationship 3352: S0090 — uses → T1056.001

**Source object:** [[01 ATT&CK/S0090 - Rover|S0090: Rover]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1056.001 - Keylogging|T1056.001: Keylogging]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Rover](https://attack.mitre.org/software/S0090) has keylogging functionality.(Citation: Palo Alto Rover)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--f4480854-9424-49d5-8b54-f839302e3ee7`.
