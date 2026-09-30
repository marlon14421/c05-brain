---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0296"
target_object: "T1557"
stix_relationship_id: "relationship--58bbe5a4-6de5-48e3-a003-028348c408ce"
---
# Relationship 1870: DET0296 — detects → T1557

**Source object:** [[01 ATT&CK/DET0296 - Detect Adversary-in-the-Middle via Network and Configuration Anomalies|DET0296: Detect Adversary-in-the-Middle via Network and Configuration Anomalies]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1557 - Adversary-in-the-Middle|T1557: Adversary-in-the-Middle]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--58bbe5a4-6de5-48e3-a003-028348c408ce`.
