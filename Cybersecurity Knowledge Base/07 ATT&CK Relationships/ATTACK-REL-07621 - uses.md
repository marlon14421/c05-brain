---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0272"
target_object: "T1033"
stix_relationship_id: "relationship--06ef19c1-8490-42cc-b345-45f3aa29fc5f"
---
# Relationship 7621: S0272 — uses → T1033

**Source object:** [[01 ATT&CK/S0272 - NDiskMonitor|S0272: NDiskMonitor]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1033 - System Owner-User Discovery|T1033: System Owner/User Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[NDiskMonitor](https://attack.mitre.org/software/S0272) obtains the victim username and encrypts the information to send over its C2 channel.(Citation: TrendMicro Patchwork Dec 2017)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--06ef19c1-8490-42cc-b345-45f3aa29fc5f`.
