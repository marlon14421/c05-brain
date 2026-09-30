---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0368"
target_object: "T1195.003"
stix_relationship_id: "relationship--37fa991d-a766-4131-9843-441d5bbe763b"
---
# Relationship 1976: DET0368 — detects → T1195.003

**Source object:** [[01 ATT&CK/DET0368 - Hardware Supply Chain Compromise Detection via Host Status & Boot Integrity Checks|DET0368: Hardware Supply Chain Compromise Detection via Host Status & Boot Integrity Checks]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1195.003 - Compromise Hardware Supply Chain|T1195.003: Compromise Hardware Supply Chain]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--37fa991d-a766-4131-9843-441d5bbe763b`.
