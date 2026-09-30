---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0229"
target_object: "T1057"
stix_relationship_id: "relationship--1fbd687c-3e02-43b8-a160-4319a7d754ac"
---
# Relationship 3766: S0229 — uses → T1057

**Source object:** [[01 ATT&CK/S0229 - Orz|S0229: Orz]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1057 - Process Discovery|T1057: Process Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Orz](https://attack.mitre.org/software/S0229) can gather a process list from the victim.(Citation: Proofpoint Leviathan Oct 2017)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--1fbd687c-3e02-43b8-a160-4319a7d754ac`.
