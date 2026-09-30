---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0094"
target_object: "T1070.004"
stix_relationship_id: "relationship--4cd705fd-5192-4248-9627-4f6cf2d4c459"
---
# Relationship 4842: G0094 — uses → T1070.004

**Source object:** [[01 ATT&CK/G0094 - Kimsuky|G0094: Kimsuky]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1070.004 - File Deletion|T1070.004: File Deletion]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Kimsuky](https://attack.mitre.org/groups/G0094) has deleted the exfiltrated data on disk after transmission. [Kimsuky](https://attack.mitre.org/groups/G0094) has also used an instrumentor script to terminate browser processes running on an infected system and then delete the cookie files on disk.(Citation: Securelist Kimsuky Sept 2013)(Citation: Talos Kimsuky Nov 2021)(Citation: KISA Operation Muzabi) [Kimsuky](https://attack.mitre.org/groups/G0094) has deleted files using the `Remove-Item` PowerShell commandlet to remove traces of executed payloads.(Citation: Securonix Kimsuky February 2025) [Kimsuky](https://attack.mitre.org/groups/G0094) has also removed remnants of files used for delivery to include .log and .zip files.(Citation: Aryaka Kimsuky July 2025)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--4cd705fd-5192-4248-9627-4f6cf2d4c459`.
