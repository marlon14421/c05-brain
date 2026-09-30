---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0206"
target_object: "T1053.007"
stix_relationship_id: "relationship--849ca811-855b-4e53-bb45-540d8746f67d"
---
# Relationship 1828: DET0206 — detects → T1053.007

**Source object:** [[01 ATT&CK/DET0206 - Detection of Malicious Kubernetes CronJob Scheduling|DET0206: Detection of Malicious Kubernetes CronJob Scheduling]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1053.007 - Container Orchestration Job|T1053.007: Container Orchestration Job]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--849ca811-855b-4e53-bb45-540d8746f67d`.
