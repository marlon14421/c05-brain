---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1060"
target_object: "T1213"
stix_relationship_id: "relationship--2e1fb9b9-c5b9-42ca-9a46-afb7b03be48c"
---
# Relationship 0806: M1060 — mitigates → T1213

**Source object:** [[01 ATT&CK/M1060 - Out-of-Band Communications Channel|M1060: Out-of-Band Communications Channel]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1213 - Data from Information Repositories|T1213: Data from Information Repositories]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Create plans for leveraging a secure out-of-band communications channel, rather than existing in-network chat applications, in case of a security incident.(Citation: TrustedSec OOB Communications)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--2e1fb9b9-c5b9-42ca-9a46-afb7b03be48c`.
