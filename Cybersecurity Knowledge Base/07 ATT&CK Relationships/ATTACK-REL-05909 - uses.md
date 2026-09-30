---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0672"
target_object: "T1680"
stix_relationship_id: "relationship--be4909b2-ff92-4dca-b835-09df2b10adb2"
---
# Relationship 5909: S0672 — uses → T1680

**Source object:** [[01 ATT&CK/S0672 - Zox|S0672: Zox]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1680 - Local Storage Discovery|T1680: Local Storage Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Zox](https://attack.mitre.org/software/S0672) can enumerate attached drives.(Citation: Novetta-Axiom)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--be4909b2-ff92-4dca-b835-09df2b10adb2`.
