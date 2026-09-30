---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0605"
target_object: "T1016"
stix_relationship_id: "relationship--7869fea0-23fe-4a05-bb16-b33019b9e2c1"
---
# Relationship 3121: S0605 — uses → T1016

**Source object:** [[01 ATT&CK/S0605 - EKANS|S0605: EKANS]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1016 - System Network Configuration Discovery|T1016: System Network Configuration Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[EKANS](https://attack.mitre.org/software/S0605) can determine the domain of a compromised host.(Citation: IBM Ransomware Trends September 2020)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--7869fea0-23fe-4a05-bb16-b33019b9e2c1`.
