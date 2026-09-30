---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0662"
target_object: "T1095"
stix_relationship_id: "relationship--cbe08a78-7997-4aef-9b29-b4b002accbc3"
---
# Relationship 8595: S0662 — uses → T1095

**Source object:** [[01 ATT&CK/S0662 - RCSession|S0662: RCSession]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1095 - Non-Application Layer Protocol|T1095: Non-Application Layer Protocol]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[RCSession](https://attack.mitre.org/software/S0662) has the ability to use TCP and UDP in C2 communications.(Citation: Trend Micro DRBControl February 2020)(Citation: Profero APT27 December 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--cbe08a78-7997-4aef-9b29-b4b002accbc3`.
