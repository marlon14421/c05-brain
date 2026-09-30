---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1027"
target_object: "T1110.003"
stix_relationship_id: "relationship--c215cce3-a2f5-4534-937c-b15d7be4588c"
---
# Relationship 0254: M1027 — mitigates → T1110.003

**Source object:** [[01 ATT&CK/M1027 - Password Policies|M1027: Password Policies]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1110.003 - Password Spraying|T1110.003: Password Spraying]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Refer to NIST guidelines when creating password policies. (Citation: NIST 800-63-3)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c215cce3-a2f5-4534-937c-b15d7be4588c`.
