---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0131"
target_object: "T1048"
stix_relationship_id: "relationship--0bd2a88c-9f76-42a8-be65-ce9706760dec"
---
# Relationship 2105: DET0131 — detects → T1048

**Source object:** [[01 ATT&CK/DET0131 - Behavioral Detection Strategy for Exfiltration Over Alternative Protocol|DET0131: Behavioral Detection Strategy for Exfiltration Over Alternative Protocol]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1048 - Exfiltration Over Alternative Protocol|T1048: Exfiltration Over Alternative Protocol]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--0bd2a88c-9f76-42a8-be65-ce9706760dec`.
