---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0348"
target_object: "T1008"
stix_relationship_id: "relationship--d3e0b0b8-797f-4638-bcb6-aa688c3a0a9a"
---
# Relationship 7794: S0348 — uses → T1008

**Source object:** [[01 ATT&CK/S0348 - Cardinal RAT|S0348: Cardinal RAT]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1008 - Fallback Channels|T1008: Fallback Channels]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Cardinal RAT](https://attack.mitre.org/software/S0348) can communicate over multiple C2 host and port combinations.(Citation: PaloAlto CardinalRat Apr 2017)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--d3e0b0b8-797f-4638-bcb6-aa688c3a0a9a`.
