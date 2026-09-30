---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0069"
target_object: "T1200"
stix_relationship_id: "relationship--a9a213e9-8227-4154-83af-2ab640f63efa"
---
# Relationship 1822: DET0069 — detects → T1200

**Source object:** [[01 ATT&CK/DET0069 - Detect unauthorized or suspicious Hardware Additions (USB-Thunderbolt-Network)|DET0069: Detect unauthorized or suspicious Hardware Additions (USB/Thunderbolt/Network)]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1200 - Hardware Additions|T1200: Hardware Additions]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--a9a213e9-8227-4154-83af-2ab640f63efa`.
