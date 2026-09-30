---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0467"
target_object: "T1518.001"
stix_relationship_id: "relationship--44aab0bc-80d5-4c6b-9acf-ceb9cc30f443"
---
# Relationship 4490: S0467 — uses → T1518.001

**Source object:** [[01 ATT&CK/S0467 - TajMahal|S0467: TajMahal]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1518.001 - Security Software Discovery|T1518.001: Security Software Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[TajMahal](https://attack.mitre.org/software/S0467) has the ability to identify which anti-virus products, firewalls, and anti-spyware products are in use.(Citation: Kaspersky TajMahal April 2019)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--44aab0bc-80d5-4c6b-9acf-ceb9cc30f443`.
