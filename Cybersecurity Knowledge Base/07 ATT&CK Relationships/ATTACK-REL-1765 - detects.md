---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0881"
target_object: "T1608.006"
stix_relationship_id: "relationship--1b09bc84-82a8-4bad-bfe8-d714bbe0fd43"
---
# Relationship 1765: DET0881 — detects → T1608.006

**Source object:** [[01 ATT&CK/DET0881 - Detection of SEO Poisoning|DET0881: Detection of SEO Poisoning]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1608.006 - SEO Poisoning|T1608.006: SEO Poisoning]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--1b09bc84-82a8-4bad-bfe8-d714bbe0fd43`.
