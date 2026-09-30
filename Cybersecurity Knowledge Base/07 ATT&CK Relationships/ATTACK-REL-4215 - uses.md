---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0184"
target_object: "T1087.002"
stix_relationship_id: "relationship--61dd6d75-a95b-488d-9a1d-924563592df7"
---
# Relationship 4215: S0184 — uses → T1087.002

**Source object:** [[01 ATT&CK/S0184 - POWRUNER|S0184: POWRUNER]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1087.002 - Domain Account|T1087.002: Domain Account]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[POWRUNER](https://attack.mitre.org/software/S0184) may collect user account information by running net user /domain or a series of other commands on a victim.(Citation: FireEye APT34 Dec 2017)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--61dd6d75-a95b-488d-9a1d-924563592df7`.
