---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0198"
target_object: "T1113"
stix_relationship_id: "relationship--ca71a63a-4481-46d2-98b2-b83cce190380"
---
# Relationship 5231: S0198 — uses → T1113

**Source object:** [[01 ATT&CK/S0198 - NETWIRE|S0198: NETWIRE]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1113 - Screen Capture|T1113: Screen Capture]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[NETWIRE](https://attack.mitre.org/software/S0198) can capture the victim's screen.(Citation: McAfee Netwire Mar 2015)(Citation: FireEye NETWIRE March 2019)(Citation: Red Canary NETWIRE January 2020)(Citation: Proofpoint NETWIRE December 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--ca71a63a-4481-46d2-98b2-b83cce190380`.
