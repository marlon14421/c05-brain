---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0044"
target_object: "T1176.001"
stix_relationship_id: "relationship--427c5505-813e-488c-92b3-2e3c15170605"
---
# Relationship 1808: DET0044 — detects → T1176.001

**Source object:** [[01 ATT&CK/DET0044 - Detecting Malicious Browser Extensions Across Platforms|DET0044: Detecting Malicious Browser Extensions Across Platforms]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1176.001 - Browser Extensions|T1176.001: Browser Extensions]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--427c5505-813e-488c-92b3-2e3c15170605`.
