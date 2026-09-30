---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1004"
target_object: "T1583.003"
stix_relationship_id: "relationship--3e375d96-bc20-431e-ab35-f2e05fb88343"
---
# Relationship 4600: G1004 — uses → T1583.003

**Source object:** [[01 ATT&CK/G1004 - LAPSUS$|G1004: LAPSUS$]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1583.003 - Virtual Private Server|T1583.003: Virtual Private Server]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[LAPSUS$](https://attack.mitre.org/groups/G1004) has used VPS hosting providers for infrastructure.(Citation: MSTIC DEV-0537 Mar 2022)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--3e375d96-bc20-431e-ab35-f2e05fb88343`.
