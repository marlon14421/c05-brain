---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0341"
target_object: "T1218.005"
stix_relationship_id: "relationship--2ed3ed76-7ebe-4371-a7e9-cc5a45ace915"
---
# Relationship 3145: S0341 — uses → T1218.005

**Source object:** [[01 ATT&CK/S0341 - Xbash|S0341: Xbash]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1218.005 - Mshta|T1218.005: Mshta]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Xbash](https://attack.mitre.org/software/S0341) can use mshta for executing scripts.(Citation: Unit42 Xbash Sept 2018)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--2ed3ed76-7ebe-4371-a7e9-cc5a45ace915`.
