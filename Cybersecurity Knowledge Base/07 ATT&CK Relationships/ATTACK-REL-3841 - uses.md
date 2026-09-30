---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0073"
target_object: "T1588.002"
stix_relationship_id: "relationship--e6b509c8-0e00-48ac-b76d-f42d18a0ae51"
---
# Relationship 3841: G0073 — uses → T1588.002

**Source object:** [[01 ATT&CK/G0073 - APT19|G0073: APT19]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1588.002 - Tool|T1588.002: Tool]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[APT19](https://attack.mitre.org/groups/G0073) has obtained and used publicly-available tools like [Empire](https://attack.mitre.org/software/S0363).(Citation: NCSC Joint Report Public Tools)(Citation: FireEye APT19)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e6b509c8-0e00-48ac-b76d-f42d18a0ae51`.
