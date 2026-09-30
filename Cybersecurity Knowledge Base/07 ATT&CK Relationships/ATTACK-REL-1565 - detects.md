---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0302"
target_object: "T1205.001"
stix_relationship_id: "relationship--e09ca94c-f233-4062-8a1c-ede510af845a"
---
# Relationship 1565: DET0302 — detects → T1205.001

**Source object:** [[01 ATT&CK/DET0302 - Port-knock → rule-daemon change → first successful connect (T1205.001)|DET0302: Port-knock → rule/daemon change → first successful connect (T1205.001)]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1205.001 - Port Knocking|T1205.001: Port Knocking]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e09ca94c-f233-4062-8a1c-ede510af845a`.
