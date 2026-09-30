---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1021"
target_object: "T1102.003"
stix_relationship_id: "relationship--b174970c-561c-4f92-9262-512d4de40e5e"
---
# Relationship 0178: M1021 — mitigates → T1102.003

**Source object:** [[01 ATT&CK/M1021 - Restrict Web-Based Content|M1021: Restrict Web-Based Content]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1102.003 - One-Way Communication|T1102.003: One-Way Communication]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Web proxies can be used to enforce external network communication policy that prevents use of unauthorized external services.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--b174970c-561c-4f92-9262-512d4de40e5e`.
