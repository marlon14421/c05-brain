---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0177"
target_object: "T1137.004"
stix_relationship_id: "relationship--48d0a0ac-28e4-43b6-824f-a7626cfc1798"
---
# Relationship 1922: DET0177 — detects → T1137.004

**Source object:** [[01 ATT&CK/DET0177 - Detect Persistence via Outlook Home Page Exploitation|DET0177: Detect Persistence via Outlook Home Page Exploitation]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1137.004 - Outlook Home Page|T1137.004: Outlook Home Page]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--48d0a0ac-28e4-43b6-824f-a7626cfc1798`.
