---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0546"
target_object: "T1078.004"
stix_relationship_id: "relationship--c5962368-c8b3-4270-822c-dd3f1afe1d01"
---
# Relationship 1754: DET0546 — detects → T1078.004

**Source object:** [[01 ATT&CK/DET0546 - Detection of Abused or Compromised Cloud Accounts for Access and Persistence|DET0546: Detection of Abused or Compromised Cloud Accounts for Access and Persistence]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1078.004 - Cloud Accounts|T1078.004: Cloud Accounts]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c5962368-c8b3-4270-822c-dd3f1afe1d01`.
