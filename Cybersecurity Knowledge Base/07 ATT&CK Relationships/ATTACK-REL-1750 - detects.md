---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0037"
target_object: "T1555.003"
stix_relationship_id: "relationship--3bd41627-e68e-455a-ae00-ee7a07b3d539"
---
# Relationship 1750: DET0037 — detects → T1555.003

**Source object:** [[01 ATT&CK/DET0037 - Detect Suspicious Access to Browser Credential Stores|DET0037: Detect Suspicious Access to Browser Credential Stores]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1555.003 - Credentials from Web Browsers|T1555.003: Credentials from Web Browsers]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--3bd41627-e68e-455a-ae00-ee7a07b3d539`.
