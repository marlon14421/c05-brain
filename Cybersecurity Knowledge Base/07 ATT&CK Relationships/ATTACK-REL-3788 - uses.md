---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0139"
target_object: "T1613"
stix_relationship_id: "relationship--40383884-c607-48ac-9522-b5b1c8e256a9"
---
# Relationship 3788: G0139 — uses → T1613

**Source object:** [[01 ATT&CK/G0139 - TeamTNT|G0139: TeamTNT]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1613 - Container and Resource Discovery|T1613: Container and Resource Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[TeamTNT](https://attack.mitre.org/groups/G0139) has checked for running containers with docker ps and for specific container names with docker inspect .(Citation: Trend Micro TeamTNT) [TeamTNT](https://attack.mitre.org/groups/G0139) has also searched for Kubernetes pods running in a local network.(Citation: Cisco Talos Intelligence Group)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--40383884-c607-48ac-9522-b5b1c8e256a9`.
