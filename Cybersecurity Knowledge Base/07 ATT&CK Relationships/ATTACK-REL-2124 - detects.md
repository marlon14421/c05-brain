---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0859"
target_object: "T1584.008"
stix_relationship_id: "relationship--11ae02a8-7acf-4773-94d5-e9191c5ae553"
---
# Relationship 2124: DET0859 — detects → T1584.008

**Source object:** [[01 ATT&CK/DET0859 - Detection of Network Devices|DET0859: Detection of Network Devices]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1584.008 - Network Devices|T1584.008: Network Devices]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--11ae02a8-7acf-4773-94d5-e9191c5ae553`.
