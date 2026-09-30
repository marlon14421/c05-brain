---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0433"
target_object: "T1218.013"
stix_relationship_id: "relationship--c313a043-5713-49d7-a13a-56af37ce46dd"
---
# Relationship 1712: DET0433 — detects → T1218.013

**Source object:** [[01 ATT&CK/DET0433 - Detecting Code Injection via mavinject.exe (App-V Injector)|DET0433: Detecting Code Injection via mavinject.exe (App-V Injector)]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1218.013 - Mavinject|T1218.013: Mavinject]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c313a043-5713-49d7-a13a-56af37ce46dd`.
