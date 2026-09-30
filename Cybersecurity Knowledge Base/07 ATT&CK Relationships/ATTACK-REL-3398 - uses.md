---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0127"
target_object: "S0386"
stix_relationship_id: "relationship--eca046f5-9175-4010-8297-07281f588934"
---
# Relationship 3398: G0127 — uses → S0386

**Source object:** [[01 ATT&CK/G0127 - TA551|G0127: TA551]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/S0386 - Ursnif|S0386: Ursnif]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

(Citation: Cybereason Valak May 2020)(Citation: Unit 42 Valak July 2020)(Citation: Unit 42 TA551 Jan 2021)(Citation: Secureworks GOLD CABIN)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--eca046f5-9175-4010-8297-07281f588934`.
