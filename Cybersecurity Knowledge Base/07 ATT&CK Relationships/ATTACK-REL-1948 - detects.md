---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0248"
target_object: "T1204.003"
stix_relationship_id: "relationship--3ce513f0-6c41-477f-a35d-42d0ec2f8171"
---
# Relationship 1948: DET0248 — detects → T1204.003

**Source object:** [[01 ATT&CK/DET0248 - User Execution – Malicious Image (containers & IaaS) – pull-run → start → anomalous b|DET0248: User Execution – Malicious Image (containers & IaaS) – pull/run → start → anomalous behavior (T1204.003)]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1204.003 - Malicious Image|T1204.003: Malicious Image]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--3ce513f0-6c41-477f-a35d-42d0ec2f8171`.
