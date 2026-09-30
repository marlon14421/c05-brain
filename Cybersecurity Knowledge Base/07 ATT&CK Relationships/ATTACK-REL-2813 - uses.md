---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S9043"
target_object: "T1087.004"
stix_relationship_id: "relationship--9e96af6e-01a0-40b3-bb2c-14fe9ee81007"
---
# Relationship 2813: S9043 — uses → T1087.004

**Source object:** [[01 ATT&CK/S9043 - Mini Shai-Hulud|S9043: Mini Shai-Hulud]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1087.004 - Cloud Account|T1087.004: Cloud Account]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Mini Shai-Hulud](https://attack.mitre.org/software/S9043) has enumerated cloud accounts and subscriptions accessible to the targeted identity.(Citation: Hunt.io TeamPCP Toolkit MAY 2026)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--9e96af6e-01a0-40b3-bb2c-14fe9ee81007`.
