---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0056"
target_object: "T1189"
stix_relationship_id: "relationship--e898946c-2c9d-4bf4-9253-67acfadc5b0a"
---
# Relationship 3430: G0056 — uses → T1189

**Source object:** [[01 ATT&CK/G0056 - PROMETHIUM|G0056: PROMETHIUM]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1189 - Drive-by Compromise|T1189: Drive-by Compromise]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[PROMETHIUM](https://attack.mitre.org/groups/G0056) has used watering hole attacks to deliver malicious versions of legitimate installers.(Citation: Bitdefender StrongPity June 2020)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e898946c-2c9d-4bf4-9253-67acfadc5b0a`.
