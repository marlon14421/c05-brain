---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0120"
target_object: "T1531"
stix_relationship_id: "relationship--5f0be570-0bb8-4d1a-913c-9fe95e22ea9b"
---
# Relationship 1816: DET0120 — detects → T1531

**Source object:** [[01 ATT&CK/DET0120 - Account Access Removal via Multi-Platform Audit Correlation|DET0120: Account Access Removal via Multi-Platform Audit Correlation]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1531 - Account Access Removal|T1531: Account Access Removal]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--5f0be570-0bb8-4d1a-913c-9fe95e22ea9b`.
