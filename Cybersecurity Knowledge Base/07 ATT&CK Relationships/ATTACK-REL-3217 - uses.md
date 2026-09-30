---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1020"
target_object: "T1036.003"
stix_relationship_id: "relationship--d04af539-cfb6-4662-8d5a-82dc85cfab1b"
---
# Relationship 3217: S1020 — uses → T1036.003

**Source object:** [[01 ATT&CK/S1020 - Kevin|S1020: Kevin]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1036.003 - Rename Legitimate Utilities|T1036.003: Rename Legitimate Utilities]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Kevin](https://attack.mitre.org/software/S1020) has renamed an image of `cmd.exe` with a random name followed by a `.tmpl` extension.(Citation: Kaspersky Lyceum October 2021)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--d04af539-cfb6-4662-8d5a-82dc85cfab1b`.
