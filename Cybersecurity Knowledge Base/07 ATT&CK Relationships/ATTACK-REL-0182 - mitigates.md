---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1032"
target_object: "T1556.006"
stix_relationship_id: "relationship--eb985609-6a5f-4e44-9bae-bfbc1e93d978"
---
# Relationship 0182: M1032 — mitigates → T1556.006

**Source object:** [[01 ATT&CK/M1032 - Multi-factor Authentication|M1032: Multi-factor Authentication]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1556.006 - Multi-Factor Authentication|T1556.006: Multi-Factor Authentication]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Ensure that MFA and MFA policies and requirements are properly implemented for existing and deactivated or dormant accounts and devices. If possible, consider configuring MFA solutions to "fail closed" rather than grant access in case of serious errors.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--eb985609-6a5f-4e44-9bae-bfbc1e93d978`.
