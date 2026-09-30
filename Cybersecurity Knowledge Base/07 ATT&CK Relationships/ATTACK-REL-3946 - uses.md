---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1229"
target_object: "T1005"
stix_relationship_id: "relationship--c13cb2e5-09cb-4fcd-9fdb-58b147a25781"
---
# Relationship 3946: S1229 — uses → T1005

**Source object:** [[01 ATT&CK/S1229 - Havoc|S1229: Havoc]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1005 - Data from Local System|T1005: Data from Local System]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Havoc](https://attack.mitre.org/software/S1229) can download files from the victim's computer.(Citation: Havoc Framework Documentation)(Citation: Immersive Labs Havoc C2 APR 2024)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c13cb2e5-09cb-4fcd-9fdb-58b147a25781`.
