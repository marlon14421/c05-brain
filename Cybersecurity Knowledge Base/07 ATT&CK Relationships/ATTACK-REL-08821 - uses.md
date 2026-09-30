---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1141"
target_object: "T1090"
stix_relationship_id: "relationship--d403d31c-59d6-42bf-91c5-728e14a3f60c"
---
# Relationship 8821: S1141 — uses → T1090

**Source object:** [[01 ATT&CK/S1141 - LunarWeb|S1141: LunarWeb]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1090 - Proxy|T1090: Proxy]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[LunarWeb](https://attack.mitre.org/software/S1141) has the ability to use a HTTP proxy server for C&C communications.(Citation: ESET Turla Lunar toolset May 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--d403d31c-59d6-42bf-91c5-728e14a3f60c`.
