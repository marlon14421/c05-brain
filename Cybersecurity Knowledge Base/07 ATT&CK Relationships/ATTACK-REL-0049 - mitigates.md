---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1019"
target_object: "T1684.001"
stix_relationship_id: "relationship--9fbfdfe8-abe8-4c09-9d34-f0825b061cfa"
---
# Relationship 0049: M1019 — mitigates → T1684.001

**Source object:** [[01 ATT&CK/M1019 - Threat Intelligence Program|M1019: Threat Intelligence Program]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1684.001 - Impersonation|T1684.001: Impersonation]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Threat intelligence helps defenders and users be aware of and defend against common lures and active campaigns that have been used for impersonation.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--9fbfdfe8-abe8-4c09-9d34-f0825b061cfa`.
