---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0606"
target_object: "T1189"
stix_relationship_id: "relationship--5ac3cb45-2d9c-42da-b35f-8f797c2e1ef8"
---
# Relationship 3122: S0606 — uses → T1189

**Source object:** [[01 ATT&CK/S0606 - Bad Rabbit|S0606: Bad Rabbit]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1189 - Drive-by Compromise|T1189: Drive-by Compromise]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Bad Rabbit](https://attack.mitre.org/software/S0606) spread through watering holes on popular sites by injecting JavaScript into the HTML body or a .js file.(Citation: ESET Bad Rabbit)(Citation: Secure List Bad Rabbit)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--5ac3cb45-2d9c-42da-b35f-8f797c2e1ef8`.
