---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1021"
target_object: "T1567.003"
stix_relationship_id: "relationship--df392629-4630-44a8-92a2-418b414a793b"
---
# Relationship 0288: M1021 — mitigates → T1567.003

**Source object:** [[01 ATT&CK/M1021 - Restrict Web-Based Content|M1021: Restrict Web-Based Content]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1567.003 - Exfiltration to Text Storage Sites|T1567.003: Exfiltration to Text Storage Sites]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Web proxies can be used to enforce an external network communication policy that prevents use of unauthorized external services.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--df392629-4630-44a8-92a2-418b414a793b`.
