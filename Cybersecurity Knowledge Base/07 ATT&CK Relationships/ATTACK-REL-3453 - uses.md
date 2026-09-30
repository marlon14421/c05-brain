---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0139"
target_object: "T1610"
stix_relationship_id: "relationship--3e62e520-0104-4be7-b4e2-d68fa88d7067"
---
# Relationship 3453: G0139 — uses → T1610

**Source object:** [[01 ATT&CK/G0139 - TeamTNT|G0139: TeamTNT]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1610 - Deploy Container|T1610: Deploy Container]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[TeamTNT](https://attack.mitre.org/groups/G0139) has deployed different types of containers into victim environments to facilitate execution.(Citation: Intezer TeamTNT September 2020)(Citation: Trend Micro TeamTNT) [TeamTNT](https://attack.mitre.org/groups/G0139) has also transferred cryptocurrency mining software to Kubernetes clusters discovered within local IP address ranges.(Citation: Cisco Talos Intelligence Group)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--3e62e520-0104-4be7-b4e2-d68fa88d7067`.
