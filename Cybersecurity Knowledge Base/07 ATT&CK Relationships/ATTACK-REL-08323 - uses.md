---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0467"
target_object: "T1518"
stix_relationship_id: "relationship--8455e704-68fd-4610-b63d-0d124a660802"
---
# Relationship 8323: S0467 — uses → T1518

**Source object:** [[01 ATT&CK/S0467 - TajMahal|S0467: TajMahal]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1518 - Software Discovery|T1518: Software Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[TajMahal](https://attack.mitre.org/software/S0467) has the ability to identify the Internet Explorer (IE) version on an infected host.(Citation: Kaspersky TajMahal April 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--8455e704-68fd-4610-b63d-0d124a660802`.
