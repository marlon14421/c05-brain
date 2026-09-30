---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0500"
target_object: "T1036.005"
stix_relationship_id: "relationship--81791886-02a4-4417-a2e7-d44f5a7f83bf"
---
# Relationship 4010: S0500 — uses → T1036.005

**Source object:** [[01 ATT&CK/S0500 - MCMD|S0500: MCMD]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1036.005 - Match Legitimate Resource Name or Location|T1036.005: Match Legitimate Resource Name or Location]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[MCMD](https://attack.mitre.org/software/S0500) has been named Readme.txt to appear legitimate.(Citation: Secureworks MCMD July 2019)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--81791886-02a4-4417-a2e7-d44f5a7f83bf`.
