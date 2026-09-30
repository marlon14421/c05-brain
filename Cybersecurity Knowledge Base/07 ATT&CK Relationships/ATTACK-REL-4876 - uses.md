---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1051"
target_object: "T1650"
stix_relationship_id: "relationship--49fe715a-116a-4ecd-9973-00ac71519c45"
---
# Relationship 4876: G1051 — uses → T1650

**Source object:** [[01 ATT&CK/G1051 - Medusa Group|G1051: Medusa Group]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1650 - Acquire Access|T1650: Acquire Access]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Medusa Group](https://attack.mitre.org/groups/G1051) has purchased user credentials and other sensitive data from Initial Access Brokers (IABs).(Citation: Palo Alto Unit 42 Medusa Group Medusa Ransomware January 2024)(Citation: Check Point Medusa Ransomware April 2025)(Citation: CISA Medusa Group Medusa Ransomware March 2025)(Citation: Intel471 Medusa Ransomware May 2025)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--49fe715a-116a-4ecd-9973-00ac71519c45`.
