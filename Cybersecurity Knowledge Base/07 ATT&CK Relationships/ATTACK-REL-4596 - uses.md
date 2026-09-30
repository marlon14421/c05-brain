---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S9014"
target_object: "T1036.003"
stix_relationship_id: "relationship--36eb9498-c6eb-4cdc-bbb0-274135fe03a1"
---
# Relationship 4596: S9014 — uses → T1036.003

**Source object:** [[01 ATT&CK/S9014 - PHASEJAM|S9014: PHASEJAM]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1036.003 - Rename Legitimate Utilities|T1036.003: Rename Legitimate Utilities]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[PHASEJAM](https://attack.mitre.org/software/S9014) has renamed the file `/home/bin/remotedebug` to `remotedebug.bak`, allowing the threats actors to write a malicious `/home/bin/remotedebug` shell script.(Citation: Google UNC5221 Ivanti January 2025)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--36eb9498-c6eb-4cdc-bbb0-274135fe03a1`.
