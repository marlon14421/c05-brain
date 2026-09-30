---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0484"
target_object: "T1530"
stix_relationship_id: "relationship--5a06a041-1cfe-4276-ba47-de008a6f56a3"
---
# Relationship 1675: DET0484 — detects → T1530

**Source object:** [[01 ATT&CK/DET0484 - Multi-Platform Cloud Storage Exfiltration Behavior Chain|DET0484: Multi-Platform Cloud Storage Exfiltration Behavior Chain]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1530 - Data from Cloud Storage|T1530: Data from Cloud Storage]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--5a06a041-1cfe-4276-ba47-de008a6f56a3`.
