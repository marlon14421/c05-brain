---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0336"
target_object: "T1554"
stix_relationship_id: "relationship--3e8f14c9-f336-4f2a-ad91-5d82669d1d90"
---
# Relationship 1719: DET0336 — detects → T1554

**Source object:** [[01 ATT&CK/DET0336 - Detect Compromise of Host Software Binaries|DET0336: Detect Compromise of Host Software Binaries]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1554 - Compromise Host Software Binary|T1554: Compromise Host Software Binary]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--3e8f14c9-f336-4f2a-ad91-5d82669d1d90`.
