---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1039"
target_object: "T1070.003"
stix_relationship_id: "relationship--dcc531dd-6136-44ac-963b-3ebab0028d96"
---
# Relationship 0973: M1039 — mitigates → T1070.003

**Source object:** [[01 ATT&CK/M1039 - Environment Variable Permissions|M1039: Environment Variable Permissions]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1070.003 - Clear Command History|T1070.003: Clear Command History]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Making the environment variables associated with command history read only may ensure that the history is preserved.(Citation: Securing bash history)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--dcc531dd-6136-44ac-963b-3ebab0028d96`.
