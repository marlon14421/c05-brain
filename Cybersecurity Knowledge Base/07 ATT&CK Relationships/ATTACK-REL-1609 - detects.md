---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0057"
target_object: "T1555.002"
stix_relationship_id: "relationship--c762f33f-8337-4d4a-b48c-6f1a4dc90bf6"
---
# Relationship 1609: DET0057 — detects → T1555.002

**Source object:** [[01 ATT&CK/DET0057 - Detect Suspicious Access to securityd Memory for Credential Extraction|DET0057: Detect Suspicious Access to securityd Memory for Credential Extraction]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1555.002 - Securityd Memory|T1555.002: Securityd Memory]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c762f33f-8337-4d4a-b48c-6f1a4dc90bf6`.
