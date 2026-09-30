---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0559"
target_object: "T1529"
stix_relationship_id: "relationship--a50b52d6-3634-4b87-8169-673ec219ce0b"
---
# Relationship 1929: DET0559 — detects → T1529

**Source object:** [[01 ATT&CK/DET0559 - Multi-Platform Shutdown or Reboot Detection via Execution and Host Status Events|DET0559: Multi-Platform Shutdown or Reboot Detection via Execution and Host Status Events]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1529 - System Shutdown-Reboot|T1529: System Shutdown/Reboot]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--a50b52d6-3634-4b87-8169-673ec219ce0b`.
