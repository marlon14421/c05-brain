---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1004"
target_object: "T1586.002"
stix_relationship_id: "relationship--beaf6c2d-e416-4edc-8091-414eee53f604"
---
# Relationship 4759: G1004 — uses → T1586.002

**Source object:** [[01 ATT&CK/G1004 - LAPSUS$|G1004: LAPSUS$]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1586.002 - Email Accounts|T1586.002: Email Accounts]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[LAPSUS$](https://attack.mitre.org/groups/G1004) has payed employees, suppliers, and business partners of target organizations for credentials.(Citation: MSTIC DEV-0537 Mar 2022)(Citation: NCC Group LAPSUS Apr 2022)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--beaf6c2d-e416-4edc-8091-414eee53f604`.
