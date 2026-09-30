---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1024"
target_object: "T1567.002"
stix_relationship_id: "relationship--036b0dfd-5d52-4b10-9951-8d967fc8df3c"
---
# Relationship 3687: G1024 — uses → T1567.002

**Source object:** [[01 ATT&CK/G1024 - Akira|G1024: Akira]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1567.002 - Exfiltration to Cloud Storage|T1567.002: Exfiltration to Cloud Storage]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Akira](https://attack.mitre.org/groups/G1024) will exfiltrate victim data using applications such as [Rclone](https://attack.mitre.org/software/S1040).(Citation: Secureworks GOLD SAHARA)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--036b0dfd-5d52-4b10-9951-8d967fc8df3c`.
