---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0661"
target_object: "T1620"
stix_relationship_id: "relationship--dbeb509e-58a9-41f9-bd08-95b3b1075edf"
---
# Relationship 8312: S0661 — uses → T1620

**Source object:** [[01 ATT&CK/S0661 - FoggyWeb|S0661: FoggyWeb]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1620 - Reflective Code Loading|T1620: Reflective Code Loading]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[FoggyWeb](https://attack.mitre.org/software/S0661)'s loader has reflectively loaded .NET-based assembly/payloads into memory.(Citation: MSTIC FoggyWeb September 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--dbeb509e-58a9-41f9-bd08-95b3b1075edf`.
