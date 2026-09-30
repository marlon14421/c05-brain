---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0232"
target_object: "T1003"
stix_relationship_id: "relationship--7ad1bbdf-4a00-426a-b130-fb4425ad2622"
---
# Relationship 3764: S0232 — uses → T1003

**Source object:** [[01 ATT&CK/S0232 - HOMEFRY|S0232: HOMEFRY]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1003 - OS Credential Dumping|T1003: OS Credential Dumping]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[HOMEFRY](https://attack.mitre.org/software/S0232) can perform credential dumping.(Citation: FireEye Periscope March 2018)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--7ad1bbdf-4a00-426a-b130-fb4425ad2622`.
