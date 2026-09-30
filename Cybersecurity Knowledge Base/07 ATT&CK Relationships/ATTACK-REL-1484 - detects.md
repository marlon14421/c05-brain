---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0363"
target_object: "T1003.001"
stix_relationship_id: "relationship--7740826e-65ad-4fa8-853a-c4f09ed81f5f"
---
# Relationship 1484: DET0363 — detects → T1003.001

**Source object:** [[01 ATT&CK/DET0363 - Detection of Credential Dumping from LSASS Memory via Access and Dump Sequence|DET0363: Detection of Credential Dumping from LSASS Memory via Access and Dump Sequence]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1003.001 - LSASS Memory|T1003.001: LSASS Memory]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--7740826e-65ad-4fa8-853a-c4f09ed81f5f`.
