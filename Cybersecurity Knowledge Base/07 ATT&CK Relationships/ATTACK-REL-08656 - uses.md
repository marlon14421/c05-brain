---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1066"
target_object: "T1574.012"
stix_relationship_id: "relationship--35dde9bf-4f03-4244-ae30-d2ddfdc450b1"
---
# Relationship 8656: S1066 — uses → T1574.012

**Source object:** [[01 ATT&CK/S1066 - DarkTortilla|S1066: DarkTortilla]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1574.012 - COR_PROFILER|T1574.012: COR_PROFILER]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[DarkTortilla](https://attack.mitre.org/software/S1066) can detect profilers by verifying the `COR_ENABLE_PROFILING` environment variable is present and active.(Citation: Secureworks DarkTortilla Aug 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--35dde9bf-4f03-4244-ae30-d2ddfdc450b1`.
