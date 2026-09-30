---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1046"
target_object: "T1219.002"
stix_relationship_id: "relationship--3396c5b4-3f52-498d-9dfd-812fb0acd543"
---
# Relationship 4690: G1046 — uses → T1219.002

**Source object:** [[01 ATT&CK/G1046 - Storm-1811|G1046: Storm-1811]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1219.002 - Remote Desktop Software|T1219.002: Remote Desktop Software]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Storm-1811](https://attack.mitre.org/groups/G1046) has abused multiple types of legitimate remote access software and tools, such as ScreenConnect, NetSupport Manager, and AnyDesk.(Citation: Microsoft Storm-1811 2024)(Citation: rapid7-email-bombing)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--3396c5b4-3f52-498d-9dfd-812fb0acd543`.
