---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0391"
target_object: "T1559.002"
stix_relationship_id: "relationship--160a52b3-8acd-4f19-810f-ac4ce96319d3"
---
# Relationship 6227: S0391 — uses → T1559.002

**Source object:** [[01 ATT&CK/S0391 - HAWKBALL|S0391: HAWKBALL]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1559.002 - Dynamic Data Exchange|T1559.002: Dynamic Data Exchange]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[HAWKBALL](https://attack.mitre.org/software/S0391) has used an OLE object that uses Equation Editor to drop the embedded shellcode.(Citation: FireEye HAWKBALL Jun 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--160a52b3-8acd-4f19-810f-ac4ce96319d3`.
