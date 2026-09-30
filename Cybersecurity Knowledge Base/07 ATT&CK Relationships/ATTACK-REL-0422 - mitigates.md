---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1040"
target_object: "T1564.014"
stix_relationship_id: "relationship--9ad3e3f4-5db6-44c9-8b67-308eb1087751"
---
# Relationship 0422: M1040 — mitigates → T1564.014

**Source object:** [[01 ATT&CK/M1040 - Behavior Prevention on Endpoint|M1040: Behavior Prevention on Endpoint]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1564.014 - Extended Attributes|T1564.014: Extended Attributes]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

During artifact review, packaging, or deployment stages, scan extended attributes alongside file contents to detect hidden payloads, obfuscated data, or suspicious attribute keys that may indicate malicious behavior.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--9ad3e3f4-5db6-44c9-8b67-308eb1087751`.
