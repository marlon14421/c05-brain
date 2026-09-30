---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0272"
target_object: "T1082"
stix_relationship_id: "relationship--7a8a36ee-66f8-42ca-abeb-29e6223b91ee"
---
# Relationship 9956: S0272 — uses → T1082

**Source object:** [[01 ATT&CK/S0272 - NDiskMonitor|S0272: NDiskMonitor]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1082 - System Information Discovery|T1082: System Information Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[NDiskMonitor](https://attack.mitre.org/software/S0272) obtains the victim computer name and encrypts the information to send over its C2 channel.(Citation: TrendMicro Patchwork Dec 2017)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--7a8a36ee-66f8-42ca-abeb-29e6223b91ee`.
