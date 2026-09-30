---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1039"
target_object: "T1690"
stix_relationship_id: "relationship--35b02fec-fa40-4282-ae43-1af7c618cdb7"
---
# Relationship 1328: M1039 — mitigates → T1690

**Source object:** [[01 ATT&CK/M1039 - Environment Variable Permissions|M1039: Environment Variable Permissions]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1690 - Prevent Command History Logging|T1690: Prevent Command History Logging]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Prevent users from changing the HISTCONTROL , HISTFILE , and HISTFILESIZE environment variables. (Citation: Securing bash history)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--35b02fec-fa40-4282-ae43-1af7c618cdb7`.
