---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1183"
target_object: "T1036.003"
stix_relationship_id: "relationship--3971fa3e-6ed3-4bc0-84d6-115431ac8d96"
---
# Relationship 4986: S1183 — uses → T1036.003

**Source object:** [[01 ATT&CK/S1183 - StrelaStealer|S1183: StrelaStealer]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1036.003 - Rename Legitimate Utilities|T1036.003: Rename Legitimate Utilities]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[StrelaStealer](https://attack.mitre.org/software/S1183) has used a renamed, legitimate `msinfo32.exe` executable to sideload the [StrelaStealer](https://attack.mitre.org/software/S1183) payload during initial installation.(Citation: DCSO StrelaStealer 2022)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--3971fa3e-6ed3-4bc0-84d6-115431ac8d96`.
