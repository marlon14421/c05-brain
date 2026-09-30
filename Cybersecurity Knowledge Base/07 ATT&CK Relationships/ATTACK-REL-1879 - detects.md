---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0851"
target_object: "T1585.001"
stix_relationship_id: "relationship--bbdb0616-dd20-4b4f-82ea-c6ebc5a9679b"
---
# Relationship 1879: DET0851 — detects → T1585.001

**Source object:** [[01 ATT&CK/DET0851 - Detection of Social Media Accounts|DET0851: Detection of Social Media Accounts]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1585.001 - Social Media Accounts|T1585.001: Social Media Accounts]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--bbdb0616-dd20-4b4f-82ea-c6ebc5a9679b`.
