---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0004"
target_object: "T1133"
stix_relationship_id: "relationship--8f354951-cd88-4193-b3d5-b95038938c7f"
---
# Relationship 3065: C0004 — uses → T1133

**Source object:** [[01 ATT&CK/C0004 - CostaRicto|C0004: CostaRicto]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1133 - External Remote Services|T1133: External Remote Services]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

During [CostaRicto](https://attack.mitre.org/campaigns/C0004), the threat actors set up remote tunneling using an SSH tool to maintain access to a compromised environment.(Citation: BlackBerry CostaRicto November 2020)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--8f354951-cd88-4193-b3d5-b95038938c7f`.
