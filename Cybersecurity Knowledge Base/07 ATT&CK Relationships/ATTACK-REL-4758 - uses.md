---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0044"
target_object: "T1057"
stix_relationship_id: "relationship--1923a47b-5a48-44e6-883f-ca23a96fea46"
---
# Relationship 4758: S0044 — uses → T1057

**Source object:** [[01 ATT&CK/S0044 - JHUHUGIT|S0044: JHUHUGIT]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1057 - Process Discovery|T1057: Process Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[JHUHUGIT](https://attack.mitre.org/software/S0044) obtains a list of running processes on the victim.(Citation: ESET Sednit Part 1)(Citation: Unit 42 Sofacy Feb 2018)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--1923a47b-5a48-44e6-883f-ca23a96fea46`.
