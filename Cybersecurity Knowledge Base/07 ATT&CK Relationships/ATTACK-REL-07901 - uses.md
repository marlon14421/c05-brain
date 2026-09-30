---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0239"
target_object: "T1070.006"
stix_relationship_id: "relationship--26352538-769c-42c0-9e38-0338c5891432"
---
# Relationship 7901: S0239 — uses → T1070.006

**Source object:** [[01 ATT&CK/S0239 - Bankshot|S0239: Bankshot]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1070.006 - Timestomp|T1070.006: Timestomp]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Bankshot](https://attack.mitre.org/software/S0239) modifies the time of a file as specified by the control server.(Citation: McAfee Bankshot)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--26352538-769c-42c0-9e38-0338c5891432`.
