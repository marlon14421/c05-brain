---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1048"
target_object: "T1685"
stix_relationship_id: "relationship--060fbd8f-3413-4bae-8a59-fe8de8bb1fb7"
---
# Relationship 3434: S1048 — uses → T1685

**Source object:** [[01 ATT&CK/S1048 - macOS.OSAMiner|S1048: macOS.OSAMiner]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1685 - Disable or Modify Tools|T1685: Disable or Modify Tools]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[macOS.OSAMiner](https://attack.mitre.org/software/S1048) has searched for the Activity Monitor process in the System Events process list and kills the process if running. [macOS.OSAMiner](https://attack.mitre.org/software/S1048) also searches the operating system's `install.log` for apps matching its hardcoded list, killing all matching process names.(Citation: SentinelLabs reversing run-only applescripts 2021)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--060fbd8f-3413-4bae-8a59-fe8de8bb1fb7`.
