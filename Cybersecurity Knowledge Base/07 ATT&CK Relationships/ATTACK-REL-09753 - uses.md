---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1164"
target_object: "T1070.006"
stix_relationship_id: "relationship--ae29058c-c1ff-43a3-bc72-cc7570f8ff46"
---
# Relationship 9753: S1164 — uses → T1070.006

**Source object:** [[01 ATT&CK/S1164 - UPSTYLE|S1164: UPSTYLE]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1070.006 - Timestomp|T1070.006: Timestomp]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[UPSTYLE](https://attack.mitre.org/software/S1164) restores timestamps to original values following modification.(Citation: Volexity UPSTYLE 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--ae29058c-c1ff-43a3-bc72-cc7570f8ff46`.
