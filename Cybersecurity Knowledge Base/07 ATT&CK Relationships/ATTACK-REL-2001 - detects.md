---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0865"
target_object: "T1598.002"
stix_relationship_id: "relationship--dbe9c063-1d79-4e02-b1b7-a775993ca3c7"
---
# Relationship 2001: DET0865 — detects → T1598.002

**Source object:** [[01 ATT&CK/DET0865 - Detection of Spearphishing Attachment|DET0865: Detection of Spearphishing Attachment]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1598.002 - Spearphishing Attachment|T1598.002: Spearphishing Attachment]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--dbe9c063-1d79-4e02-b1b7-a775993ca3c7`.
