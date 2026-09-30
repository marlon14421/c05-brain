---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0066"
target_object: "T1204.001"
stix_relationship_id: "relationship--8f834d41-f4f4-4662-88a2-bfe298515b91"
---
# Relationship 1749: DET0066 — detects → T1204.001

**Source object:** [[01 ATT&CK/DET0066 - User Execution – Malicious Link (click → suspicious egress → download-write → follow-|DET0066: User Execution – Malicious Link (click → suspicious egress → download/write → follow-on activity)]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1204.001 - Malicious Link|T1204.001: Malicious Link]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--8f834d41-f4f4-4662-88a2-bfe298515b91`.
