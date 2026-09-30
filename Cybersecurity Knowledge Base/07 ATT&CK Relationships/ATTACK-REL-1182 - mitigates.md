---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1038"
target_object: "T1553.001"
stix_relationship_id: "relationship--819bc603-b0fe-4681-a235-3c6e9a36e3b5"
---
# Relationship 1182: M1038 — mitigates → T1553.001

**Source object:** [[01 ATT&CK/M1038 - Execution Prevention|M1038: Execution Prevention]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1553.001 - Gatekeeper Bypass|T1553.001: Gatekeeper Bypass]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

System settings can prevent applications from running that haven't been downloaded through the Apple Store which can help mitigate some of these issues.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--819bc603-b0fe-4681-a235-3c6e9a36e3b5`.
