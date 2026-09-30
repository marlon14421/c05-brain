---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0238"
target_object: "T1005"
stix_relationship_id: "relationship--066d9d0e-0298-420b-ba84-a4af07211a35"
---
# Relationship 3909: S0238 — uses → T1005

**Source object:** [[01 ATT&CK/S0238 - Proxysvc|S0238: Proxysvc]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1005 - Data from Local System|T1005: Data from Local System]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Proxysvc](https://attack.mitre.org/software/S0238) searches the local system and gathers data.(Citation: McAfee GhostSecret)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--066d9d0e-0298-420b-ba84-a4af07211a35`.
