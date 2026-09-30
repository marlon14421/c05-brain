---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1015"
target_object: "T1598.004"
stix_relationship_id: "relationship--dbec2814-4a92-4ab7-a007-123b40b16d0b"
---
# Relationship 4446: G1015 — uses → T1598.004

**Source object:** [[01 ATT&CK/G1015 - Scattered Spider|G1015: Scattered Spider]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1598.004 - Spearphishing Voice|T1598.004: Spearphishing Voice]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Scattered Spider](https://attack.mitre.org/groups/G1015) has used help desk voice-based phishing and also called employees at target organizations and compelled them to navigate to fake login portals using adversary-in-the-middle toolkits.(Citation: MSTIC Octo Tempest Operations October 2023)(Citation: CrowdStrike Scattered Spider JUL 2025)(Citation: Mandiant VMware vSphere JUL 2025)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--dbec2814-4a92-4ab7-a007-123b40b16d0b`.
