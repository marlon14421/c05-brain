---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0593"
target_object: "T1003.007"
stix_relationship_id: "relationship--5b774635-ffa8-414a-8375-b8ef97c7d8b7"
---
# Relationship 1795: DET0593 — detects → T1003.007

**Source object:** [[01 ATT&CK/DET0593 - Detecting OS Credential Dumping via -proc Filesystem Access on Linux|DET0593: Detecting OS Credential Dumping via /proc Filesystem Access on Linux]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1003.007 - Proc Filesystem|T1003.007: Proc Filesystem]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--5b774635-ffa8-414a-8375-b8ef97c7d8b7`.
