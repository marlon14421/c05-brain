---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0030"
target_object: "T1113"
stix_relationship_id: "relationship--16d5d573-60bb-402c-88c3-2bc0af8388eb"
---
# Relationship 8233: S0030 — uses → T1113

**Source object:** [[01 ATT&CK/S0030 - Carbanak|S0030: Carbanak]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1113 - Screen Capture|T1113: Screen Capture]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Carbanak](https://attack.mitre.org/software/S0030) performs desktop video recording and captures screenshots of the desktop and sends it to the C2 server.(Citation: FireEye CARBANAK June 2017)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--16d5d573-60bb-402c-88c3-2bc0af8388eb`.
