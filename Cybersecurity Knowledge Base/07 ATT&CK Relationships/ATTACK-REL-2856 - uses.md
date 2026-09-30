---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0378"
target_object: "T1546.003"
stix_relationship_id: "relationship--fbce0681-c5d2-4ea9-b48a-4fc42448f9e0"
---
# Relationship 2856: S0378 — uses → T1546.003

**Source object:** [[01 ATT&CK/S0378 - PoshC2|S0378: PoshC2]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1546.003 - Windows Management Instrumentation Event Subscription|T1546.003: Windows Management Instrumentation Event Subscription]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[PoshC2](https://attack.mitre.org/software/S0378) has the ability to persist on a system using WMI events.(Citation: GitHub PoshC2)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--fbce0681-c5d2-4ea9-b48a-4fc42448f9e0`.
