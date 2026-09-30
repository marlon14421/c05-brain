---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0322"
target_object: "T1027.016"
stix_relationship_id: "relationship--0310c64d-52dc-4e99-acde-77c20d799e54"
---
# Relationship 1949: DET0322 — detects → T1027.016

**Source object:** [[01 ATT&CK/DET0322 - Detection Strategy for Junk Code Obfuscation with Suspicious Execution Patterns|DET0322: Detection Strategy for Junk Code Obfuscation with Suspicious Execution Patterns]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1027.016 - Junk Code Insertion|T1027.016: Junk Code Insertion]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--0310c64d-52dc-4e99-acde-77c20d799e54`.
