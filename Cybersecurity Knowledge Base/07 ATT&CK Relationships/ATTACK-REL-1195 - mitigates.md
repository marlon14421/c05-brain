---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1052"
target_object: "T1546.011"
stix_relationship_id: "relationship--5329d477-4378-4635-8da8-ed427d7863fc"
---
# Relationship 1195: M1052 — mitigates → T1546.011

**Source object:** [[01 ATT&CK/M1052 - User Account Control|M1052: User Account Control]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1546.011 - Application Shimming|T1546.011: Application Shimming]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Changing UAC settings to "Always Notify" will give the user more visibility when UAC elevation is requested, however, this option will not be popular among users due to the constant UAC interruptions.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--5329d477-4378-4635-8da8-ed427d7863fc`.
