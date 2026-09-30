---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0171"
target_object: "T1606.001"
stix_relationship_id: "relationship--a5166ebe-100e-4cae-abc9-2065c1d3bcd6"
---
# Relationship 1649: DET0171 — detects → T1606.001

**Source object:** [[01 ATT&CK/DET0171 - Detection Strategy for Forged Web Cookies|DET0171: Detection Strategy for Forged Web Cookies]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1606.001 - Web Cookies|T1606.001: Web Cookies]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--a5166ebe-100e-4cae-abc9-2065c1d3bcd6`.
