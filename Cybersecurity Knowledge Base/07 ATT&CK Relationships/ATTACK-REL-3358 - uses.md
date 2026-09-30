---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1071"
target_object: "T1558.004"
stix_relationship_id: "relationship--865d4dac-1c58-46ed-8b86-58ec6c2633ec"
---
# Relationship 3358: S1071 — uses → T1558.004

**Source object:** [[01 ATT&CK/S1071 - Rubeus|S1071: Rubeus]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1558.004 - AS-REP Roasting|T1558.004: AS-REP Roasting]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Rubeus](https://attack.mitre.org/software/S1071) can reveal the credentials of accounts that have Kerberos pre-authentication disabled through AS-REP roasting.(Citation: GitHub Rubeus March 2023)(Citation: DFIR Ryuk's Return October 2020)(Citation: DFIR Ryuk 2 Hour Speed Run November 2020)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--865d4dac-1c58-46ed-8b86-58ec6c2633ec`.
