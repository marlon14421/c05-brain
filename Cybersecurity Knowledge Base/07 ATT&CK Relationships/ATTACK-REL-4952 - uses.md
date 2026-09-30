---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0238"
target_object: "T1016"
stix_relationship_id: "relationship--d4d12441-c588-47f2-9751-8a86a867a185"
---
# Relationship 4952: S0238 — uses → T1016

**Source object:** [[01 ATT&CK/S0238 - Proxysvc|S0238: Proxysvc]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1016 - System Network Configuration Discovery|T1016: System Network Configuration Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Proxysvc](https://attack.mitre.org/software/S0238) collects the network adapter information and domain/username information based on current remote sessions.(Citation: McAfee GhostSecret)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--d4d12441-c588-47f2-9751-8a86a867a185`.
