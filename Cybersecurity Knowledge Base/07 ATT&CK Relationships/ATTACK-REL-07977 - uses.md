---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0632"
target_object: "T1480.002"
stix_relationship_id: "relationship--6f145407-cd6b-4e96-957f-a74cd6c84c52"
---
# Relationship 7977: S0632 — uses → T1480.002

**Source object:** [[01 ATT&CK/S0632 - GrimAgent|S0632: GrimAgent]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1480.002 - Mutual Exclusion|T1480.002: Mutual Exclusion]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[GrimAgent](https://attack.mitre.org/software/S0632) uses the last 64 bytes of the binary to compute a mutex name. If the generated name is invalid, it will default to the generic `mymutex`.(Citation: Group IB GrimAgent July 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--6f145407-cd6b-4e96-957f-a74cd6c84c52`.
