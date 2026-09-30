---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0205"
target_object: "T1220"
stix_relationship_id: "relationship--f6da3b26-449a-4b87-b2be-f203dadb6302"
---
# Relationship 1766: DET0205 — detects → T1220

**Source object:** [[01 ATT&CK/DET0205 - Detect XSL Script Abuse via msxsl and wmic|DET0205: Detect XSL Script Abuse via msxsl and wmic]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1220 - XSL Script Processing|T1220: XSL Script Processing]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--f6da3b26-449a-4b87-b2be-f203dadb6302`.
