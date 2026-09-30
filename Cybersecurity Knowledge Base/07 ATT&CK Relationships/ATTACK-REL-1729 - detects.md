---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0253"
target_object: "T1543.002"
stix_relationship_id: "relationship--03591820-bd88-4ad5-8d1b-11e8f28d495e"
---
# Relationship 1729: DET0253 — detects → T1543.002

**Source object:** [[01 ATT&CK/DET0253 - Detection of Systemd Service Creation or Modification on Linux|DET0253: Detection of Systemd Service Creation or Modification on Linux]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1543.002 - Systemd Service|T1543.002: Systemd Service]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--03591820-bd88-4ad5-8d1b-11e8f28d495e`.
