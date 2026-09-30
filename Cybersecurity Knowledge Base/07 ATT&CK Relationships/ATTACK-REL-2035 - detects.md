---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0513"
target_object: "T1003.005"
stix_relationship_id: "relationship--234074de-96c1-4eb5-968d-09bdf988cb18"
---
# Relationship 2035: DET0513 — detects → T1003.005

**Source object:** [[01 ATT&CK/DET0513 - Detection of Cached Domain Credential Dumping via Local Hash Cache Access|DET0513: Detection of Cached Domain Credential Dumping via Local Hash Cache Access]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1003.005 - Cached Domain Credentials|T1003.005: Cached Domain Credentials]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--234074de-96c1-4eb5-968d-09bdf988cb18`.
