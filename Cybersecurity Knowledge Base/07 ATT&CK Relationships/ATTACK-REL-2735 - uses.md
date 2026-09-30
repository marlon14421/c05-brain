---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0484"
target_object: "T1106"
stix_relationship_id: "relationship--caa542d3-c8b0-4d10-998d-0998be406da8"
---
# Relationship 2735: S0484 — uses → T1106

**Source object:** [[01 ATT&CK/S0484 - Carberp|S0484: Carberp]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1106 - Native API|T1106: Native API]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Carberp](https://attack.mitre.org/software/S0484) has used the NtQueryDirectoryFile and ZwQueryDirectoryFile functions to hide files and directories.(Citation: Trusteer Carberp October 2010)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--caa542d3-c8b0-4d10-998d-0998be406da8`.
