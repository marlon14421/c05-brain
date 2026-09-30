---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0007"
target_object: "S0044"
stix_relationship_id: "relationship--75d04175-c43d-46cd-be08-5f4c91f767ed"
---
# Relationship 4652: G0007 — uses → S0044

**Source object:** [[01 ATT&CK/G0007 - APT28|G0007: APT28]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/S0044 - JHUHUGIT|S0044: JHUHUGIT]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

(Citation: FireEye APT28 January 2017)(Citation: Kaspersky Sofacy)(Citation: Securelist Sofacy Feb 2018)(Citation: US District Court Indictment GRU Oct 2018)(Citation: Secureworks IRON TWILIGHT Active Measures March 2017)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--75d04175-c43d-46cd-be08-5f4c91f767ed`.
