---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1011"
target_object: "T1585.002"
stix_relationship_id: "relationship--88d72a6e-091f-48ff-9ad4-fd05d748d956"
---
# Relationship 3410: G1011 — uses → T1585.002

**Source object:** [[01 ATT&CK/G1011 - EXOTIC LILY|G1011: EXOTIC LILY]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1585.002 - Email Accounts|T1585.002: Email Accounts]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[EXOTIC LILY](https://attack.mitre.org/groups/G1011) has created e-mail accounts to spoof targeted organizations.(Citation: Google EXOTIC LILY March 2022)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--88d72a6e-091f-48ff-9ad4-fd05d748d956`.
