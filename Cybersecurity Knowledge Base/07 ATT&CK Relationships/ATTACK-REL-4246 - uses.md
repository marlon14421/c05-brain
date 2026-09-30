---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0094"
target_object: "T1053.005"
stix_relationship_id: "relationship--db2be919-e747-430b-a7ee-d619a11abd93"
---
# Relationship 4246: G0094 — uses → T1053.005

**Source object:** [[01 ATT&CK/G0094 - Kimsuky|G0094: Kimsuky]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1053.005 - Scheduled Task|T1053.005: Scheduled Task]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Kimsuky](https://attack.mitre.org/groups/G0094) has downloaded additional malware with scheduled tasks.(Citation: KISA Operation Muzabi)(Citation: NaumaanProofpoint_GlobalClickFix_April2025) [Kimsuky](https://attack.mitre.org/groups/G0094) has established persistence by creating a scheduled task named “ChromeUpdateTaskMachine” through the PowerShell cmdlet `Register-ScheduleTask` which was set to execute another PowerShell script once, then five minutes after its creation and periodically repeat every 30 minutes.(Citation: Securonix Kimsuky February 2025) [Kimsuky](https://attack.mitre.org/groups/G0094) has also set scheduled tasks that run periodically using the PT1M repetition pattern leveraging naming conventions of Anti-Virus software to include "AhnlabUpdate".(Citation: Gen Digital Kimsuky HTTPTroy October 2025)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--db2be919-e747-430b-a7ee-d619a11abd93`.
