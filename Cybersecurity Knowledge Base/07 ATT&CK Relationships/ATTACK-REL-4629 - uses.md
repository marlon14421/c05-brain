---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0611"
target_object: "T1112"
stix_relationship_id: "relationship--a5c59466-b7ac-44a0-804d-cdfbc88c8fba"
---
# Relationship 4629: S0611 — uses → T1112

**Source object:** [[01 ATT&CK/S0611 - Clop|S0611: Clop]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1112 - Modify Registry|T1112: Modify Registry]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Clop](https://attack.mitre.org/software/S0611) can make modifications to Registry keys.(Citation: Cybereason Clop Dec 2020)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--a5c59466-b7ac-44a0-804d-cdfbc88c8fba`.
