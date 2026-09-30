---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0016"
target_object: "S0032"
stix_relationship_id: "relationship--1c9d5795-fa0d-4d01-815f-eef0e4d8b2b7"
---
# Relationship 3935: C0016 — uses → S0032

**Source object:** [[01 ATT&CK/C0016 - Operation Dust Storm|C0016: Operation Dust Storm]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/S0032 - gh0st RAT|S0032: gh0st RAT]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

(Citation: Cylance Dust Storm)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--1c9d5795-fa0d-4d01-815f-eef0e4d8b2b7`.
