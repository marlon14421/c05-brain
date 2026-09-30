---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1017"
target_object: "T1684.001"
stix_relationship_id: "relationship--74a8ec0f-20d4-4175-bfc3-517d57956eff"
---
# Relationship 1002: M1017 — mitigates → T1684.001

**Source object:** [[01 ATT&CK/M1017 - User Training|M1017: User Training]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1684.001 - Impersonation|T1684.001: Impersonation]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Train users to be aware of impersonation tricks and how to counter them, for example confirming incoming requests through an independent platform like a phone call or in-person, to reduce risk.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--74a8ec0f-20d4-4175-bfc3-517d57956eff`.
