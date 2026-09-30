---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0276"
target_object: "T1207"
stix_relationship_id: "relationship--a5f42918-93c0-4537-9780-bfbe67920812"
---
# Relationship 1728: DET0276 — detects → T1207

**Source object:** [[01 ATT&CK/DET0276 - Detection Strategy for Rogue Domain Controller (DCShadow) Registration and Replicatio|DET0276: Detection Strategy for Rogue Domain Controller (DCShadow) Registration and Replication Abuse]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1207 - Rogue Domain Controller|T1207: Rogue Domain Controller]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--a5f42918-93c0-4537-9780-bfbe67920812`.
