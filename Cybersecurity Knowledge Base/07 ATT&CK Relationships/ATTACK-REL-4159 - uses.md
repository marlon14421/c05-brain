---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0006"
target_object: "T1005"
stix_relationship_id: "relationship--38a72b32-dc04-493d-8b92-31174c32f3ed"
---
# Relationship 4159: G0006 — uses → T1005

**Source object:** [[01 ATT&CK/G0006 - APT1|G0006: APT1]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1005 - Data from Local System|T1005: Data from Local System]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[APT1](https://attack.mitre.org/groups/G0006) has collected files from a local victim.(Citation: Mandiant APT1)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--38a72b32-dc04-493d-8b92-31174c32f3ed`.
