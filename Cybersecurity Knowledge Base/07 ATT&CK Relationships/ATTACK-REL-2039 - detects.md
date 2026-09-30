---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0387"
target_object: "T1557.002"
stix_relationship_id: "relationship--9b5ab78c-06dd-4baf-bca6-bee938523de1"
---
# Relationship 2039: DET0387 — detects → T1557.002

**Source object:** [[01 ATT&CK/DET0387 - Detect ARP Cache Poisoning Across Linux, Windows, and macOS|DET0387: Detect ARP Cache Poisoning Across Linux, Windows, and macOS]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1557.002 - ARP Cache Poisoning|T1557.002: ARP Cache Poisoning]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--9b5ab78c-06dd-4baf-bca6-bee938523de1`.
