---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0056"
target_object: "T1553.004"
stix_relationship_id: "relationship--ac19130e-d247-49e4-8aca-2837984906dc"
---
# Relationship 1481: DET0056 — detects → T1553.004

**Source object:** [[01 ATT&CK/DET0056 - Detection Strategy for Subvert Trust Controls via Install Root Certificate|DET0056: Detection Strategy for Subvert Trust Controls via Install Root Certificate.]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1553.004 - Install Root Certificate|T1553.004: Install Root Certificate]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--ac19130e-d247-49e4-8aca-2837984906dc`.
