---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1040"
target_object: "T1027.012"
stix_relationship_id: "relationship--9c3ee91e-c64e-47c5-8aeb-300bc8aa6b6e"
---
# Relationship 0652: M1040 — mitigates → T1027.012

**Source object:** [[01 ATT&CK/M1040 - Behavior Prevention on Endpoint|M1040: Behavior Prevention on Endpoint]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1027.012 - LNK Icon Smuggling|T1027.012: LNK Icon Smuggling]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

On Windows 10, enable Attack Surface Reduction (ASR) rules to prevent execution of potentially obfuscated scripts or payloads.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--9c3ee91e-c64e-47c5-8aeb-300bc8aa6b6e`.
