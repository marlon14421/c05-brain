---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0069"
target_object: "T1559.001"
stix_relationship_id: "relationship--319dbc0e-5026-4796-bfd9-43ef3d30eb8d"
---
# Relationship 3586: G0069 — uses → T1559.001

**Source object:** [[01 ATT&CK/G0069 - MuddyWater|G0069: MuddyWater]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1559.001 - Component Object Model|T1559.001: Component Object Model]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[MuddyWater](https://attack.mitre.org/groups/G0069) has used malware that has the capability to execute malicious code via COM, DCOM, and Outlook.(Citation: Securelist MuddyWater Oct 2018)(Citation: ClearSky MuddyWater June 2019)(Citation: DHS CISA AA22-055A MuddyWater February 2022)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--319dbc0e-5026-4796-bfd9-43ef3d30eb8d`.
