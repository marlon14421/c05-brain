---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0488"
target_object: "T1199"
stix_relationship_id: "relationship--8dcb3689-54f5-4416-9b75-6c380d24bdca"
---
# Relationship 1845: DET0488 — detects → T1199

**Source object:** [[01 ATT&CK/DET0488 - Detect abuse of Trusted Relationships (third-party and delegated admin access)|DET0488: Detect abuse of Trusted Relationships (third-party and delegated admin access)]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1199 - Trusted Relationship|T1199: Trusted Relationship]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--8dcb3689-54f5-4416-9b75-6c380d24bdca`.
