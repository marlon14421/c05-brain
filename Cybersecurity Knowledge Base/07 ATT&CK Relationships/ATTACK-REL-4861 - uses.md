---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0046"
target_object: "T1053.005"
stix_relationship_id: "relationship--1f7b17e9-9ad3-42dd-ab92-e3afe752247b"
---
# Relationship 4861: G0046 — uses → T1053.005

**Source object:** [[01 ATT&CK/G0046 - FIN7|G0046: FIN7]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1053.005 - Scheduled Task|T1053.005: Scheduled Task]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[FIN7](https://attack.mitre.org/groups/G0046) malware has created scheduled tasks to establish persistence.(Citation: FireEye FIN7 April 2017)(Citation: Morphisec FIN7 June 2017)(Citation: FireEye FIN7 Aug 2018)(Citation: Flashpoint FIN 7 March 2019) Specifically, [FIN7](https://attack.mitre.org/groups/G0046) has used OpenSSH to establish persistence.(Citation: BlackBerry_FIN7_April2024)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--1f7b17e9-9ad3-42dd-ab92-e3afe752247b`.
