---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0898"
target_object: "T1036.012"
stix_relationship_id: "relationship--4f0c1449-c5fb-4d6d-b023-4f59f3fca8b0"
---
# Relationship 1463: DET0898 — detects → T1036.012

**Source object:** [[01 ATT&CK/DET0898 - Detection of Spoofed User-Agent|DET0898: Detection of Spoofed User-Agent]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1036.012 - Browser Fingerprint|T1036.012: Browser Fingerprint]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--4f0c1449-c5fb-4d6d-b023-4f59f3fca8b0`.
