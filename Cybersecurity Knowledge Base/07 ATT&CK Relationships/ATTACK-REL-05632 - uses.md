---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1148"
target_object: "T1071.001"
stix_relationship_id: "relationship--402acc79-8d1f-41ab-80ef-559d77b145d7"
---
# Relationship 5632: S1148 — uses → T1071.001

**Source object:** [[01 ATT&CK/S1148 - Raccoon Stealer|S1148: Raccoon Stealer]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1071.001 - Web Protocols|T1071.001: Web Protocols]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Raccoon Stealer](https://attack.mitre.org/software/S1148) uses HTTP, and particularly HTTP POST requests, for command and control actions.(Citation: S2W Racoon 2022)(Citation: Sekoia Raccoon1 2022)(Citation: Sekoia Raccoon2 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--402acc79-8d1f-41ab-80ef-559d77b145d7`.
