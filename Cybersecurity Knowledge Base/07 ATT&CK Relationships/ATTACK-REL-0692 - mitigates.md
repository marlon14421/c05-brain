---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1060"
target_object: "T1489"
stix_relationship_id: "relationship--b774aa5d-7731-46b4-b285-dc1c67a0d01c"
---
# Relationship 0692: M1060 — mitigates → T1489

**Source object:** [[01 ATT&CK/M1060 - Out-of-Band Communications Channel|M1060: Out-of-Band Communications Channel]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1489 - Service Stop|T1489: Service Stop]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Develop and enforce security policies that include the use of out-of-band communication channels for critical communications during a security incident.(Citation: TrustedSec OOB Communications)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--b774aa5d-7731-46b4-b285-dc1c67a0d01c`.
