---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0049"
target_object: "T1588.002"
stix_relationship_id: "relationship--526837ff-672d-4afa-899e-3634b19bab14"
---
# Relationship 3710: G0049 — uses → T1588.002

**Source object:** [[01 ATT&CK/G0049 - OilRig|G0049: OilRig]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1588.002 - Tool|T1588.002: Tool]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[OilRig](https://attack.mitre.org/groups/G0049) has made use of the publicly available tools including Plink and [Mimikatz](https://attack.mitre.org/software/S0002).(Citation: Symantec Crambus OCT 2023)(Citation: Trend Micro Earth Simnavaz October 2024)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--526837ff-672d-4afa-899e-3634b19bab14`.
