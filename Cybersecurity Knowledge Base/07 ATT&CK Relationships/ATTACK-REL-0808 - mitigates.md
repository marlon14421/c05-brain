---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1051"
target_object: "T1212"
stix_relationship_id: "relationship--3d58c303-b76c-4acc-8856-c71e03ea5c44"
---
# Relationship 0808: M1051 — mitigates → T1212

**Source object:** [[01 ATT&CK/M1051 - Update Software|M1051: Update Software]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1212 - Exploitation for Credential Access|T1212: Exploitation for Credential Access]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Update software regularly by employing patch management for internal enterprise endpoints and servers.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--3d58c303-b76c-4acc-8856-c71e03ea5c44`.
