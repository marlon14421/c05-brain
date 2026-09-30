---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0526"
target_object: "T1518"
stix_relationship_id: "relationship--dd4c57df-6ddc-4a41-b1ee-5f72556fc57d"
---
# Relationship 4029: S0526 — uses → T1518

**Source object:** [[01 ATT&CK/S0526 - KGH_SPY|S0526: KGH_SPY]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1518 - Software Discovery|T1518: Software Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[KGH_SPY](https://attack.mitre.org/software/S0526) can collect information on installed applications.(Citation: Cybereason Kimsuky November 2020)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--dd4c57df-6ddc-4a41-b1ee-5f72556fc57d`.
