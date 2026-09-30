---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0283"
target_object: "T1029"
stix_relationship_id: "relationship--0d7811d3-d4ee-4114-b841-c0463f2274be"
---
# Relationship 4551: S0283 — uses → T1029

**Source object:** [[01 ATT&CK/S0283 - jRAT|S0283: jRAT]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1029 - Scheduled Transfer|T1029: Scheduled Transfer]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[jRAT](https://attack.mitre.org/software/S0283) can be configured to reconnect at certain intervals.(Citation: Kaspersky Adwind Feb 2016)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--0d7811d3-d4ee-4114-b841-c0463f2274be`.
