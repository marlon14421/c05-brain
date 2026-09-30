---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0662"
target_object: "T1573"
stix_relationship_id: "relationship--0a47636e-8260-414d-aff7-7b1120778a51"
---
# Relationship 4252: S0662 — uses → T1573

**Source object:** [[01 ATT&CK/S0662 - RCSession|S0662: RCSession]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1573 - Encrypted Channel|T1573: Encrypted Channel]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[RCSession](https://attack.mitre.org/software/S0662) can use an encrypted beacon to check in with C2.(Citation: Secureworks BRONZE PRESIDENT December 2019)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--0a47636e-8260-414d-aff7-7b1120778a51`.
