---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0467"
target_object: "T1119"
stix_relationship_id: "relationship--5197fd7a-766f-45da-87f5-c469377460d1"
---
# Relationship 7085: S0467 — uses → T1119

**Source object:** [[01 ATT&CK/S0467 - TajMahal|S0467: TajMahal]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1119 - Automated Collection|T1119: Automated Collection]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[TajMahal](https://attack.mitre.org/software/S0467) has the ability to index and compress files into a send queue for exfiltration.(Citation: Kaspersky TajMahal April 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--5197fd7a-766f-45da-87f5-c469377460d1`.
