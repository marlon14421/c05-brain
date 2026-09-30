---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1018"
target_object: "T1583.006"
stix_relationship_id: "relationship--e0ef0f63-9418-4258-8f0a-f752e4b4b1a0"
---
# Relationship 4626: G1018 — uses → T1583.006

**Source object:** [[01 ATT&CK/G1018 - TA2541|G1018: TA2541]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1583.006 - Web Services|T1583.006: Web Services]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[TA2541](https://attack.mitre.org/groups/G1018) has hosted malicious files on various platforms including Google Drive, OneDrive, Discord, PasteText, ShareText, and GitHub.(Citation: Proofpoint TA2541 February 2022)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e0ef0f63-9418-4258-8f0a-f752e4b4b1a0`.
