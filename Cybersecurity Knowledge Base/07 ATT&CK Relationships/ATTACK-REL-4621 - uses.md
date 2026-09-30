---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0076"
target_object: "T1219.002"
stix_relationship_id: "relationship--52f31493-1654-4516-960d-c79018f1efd8"
---
# Relationship 4621: G0076 — uses → T1219.002

**Source object:** [[01 ATT&CK/G0076 - Thrip|G0076: Thrip]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1219.002 - Remote Desktop Software|T1219.002: Remote Desktop Software]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Thrip](https://attack.mitre.org/groups/G0076) used a cloud-based remote access software called LogMeIn for their attacks.(Citation: Symantec Thrip June 2018)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--52f31493-1654-4516-960d-c79018f1efd8`.
