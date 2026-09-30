---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0129"
target_object: "T1074.001"
stix_relationship_id: "relationship--c890e6af-c827-4369-a0f7-fb351c6b6ec5"
---
# Relationship 2843: G0129 — uses → T1074.001

**Source object:** [[01 ATT&CK/G0129 - Mustang Panda|G0129: Mustang Panda]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1074.001 - Local Data Staging|T1074.001: Local Data Staging]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Mustang Panda](https://attack.mitre.org/groups/G0129) has stored collected credential files in c:\windows\temp prior to exfiltration. [Mustang Panda](https://attack.mitre.org/groups/G0129) has also stored documents for exfiltration in a hidden folder on USB drives.(Citation: Secureworks BRONZE PRESIDENT December 2019)(Citation: Avira Mustang Panda January 2020)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c890e6af-c827-4369-a0f7-fb351c6b6ec5`.
