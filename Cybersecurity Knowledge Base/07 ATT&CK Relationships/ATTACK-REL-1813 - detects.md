---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0367"
target_object: "T1037.003"
stix_relationship_id: "relationship--6cc862d2-8a97-4a53-a3c5-41615e968956"
---
# Relationship 1813: DET0367 — detects → T1037.003

**Source object:** [[01 ATT&CK/DET0367 - Detect Network Logon Script Abuse via Multi-Event Correlation on Windows|DET0367: Detect Network Logon Script Abuse via Multi-Event Correlation on Windows]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1037.003 - Network Logon Script|T1037.003: Network Logon Script]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--6cc862d2-8a97-4a53-a3c5-41615e968956`.
