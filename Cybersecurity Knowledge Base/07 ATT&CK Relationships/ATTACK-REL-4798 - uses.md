---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0532"
target_object: "T1110.001"
stix_relationship_id: "relationship--b7e456b1-ed5e-48f0-be6e-df3e7d6b4044"
---
# Relationship 4798: S0532 — uses → T1110.001

**Source object:** [[01 ATT&CK/S0532 - Lucifer|S0532: Lucifer]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1110.001 - Password Guessing|T1110.001: Password Guessing]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Lucifer](https://attack.mitre.org/software/S0532) has attempted to brute force TCP ports 135 (RPC) and 1433 (MSSQL) with the default username or list of usernames and passwords.(Citation: Unit 42 Lucifer June 2020)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--b7e456b1-ed5e-48f0-be6e-df3e7d6b4044`.
