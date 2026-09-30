---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0082"
target_object: "T1070.006"
stix_relationship_id: "relationship--6fa3a8bd-3a66-4f48-9439-97e5ae3dcac9"
---
# Relationship 6236: G0082 — uses → T1070.006

**Source object:** [[01 ATT&CK/G0082 - APT38|G0082: APT38]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1070.006 - Timestomp|T1070.006: Timestomp]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[APT38](https://attack.mitre.org/groups/G0082) has modified data timestamps to mimic files that are in the same folder on a compromised host.(Citation: CISA AA20-239A BeagleBoyz August 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--6fa3a8bd-3a66-4f48-9439-97e5ae3dcac9`.
