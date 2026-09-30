---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0495"
target_object: "T1657"
stix_relationship_id: "relationship--9ae66715-6d4e-4fb5-b359-1658c57052b1"
---
# Relationship 1925: DET0495 — detects → T1657

**Source object:** [[01 ATT&CK/DET0495 - Detection Strategy for Financial Theft|DET0495: Detection Strategy for Financial Theft]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1657 - Financial Theft|T1657: Financial Theft]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--9ae66715-6d4e-4fb5-b359-1658c57052b1`.
