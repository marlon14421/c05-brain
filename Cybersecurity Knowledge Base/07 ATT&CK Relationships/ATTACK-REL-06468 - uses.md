---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0046"
target_object: "T1608.005"
stix_relationship_id: "relationship--1f3d48af-f6e6-423b-8290-2386f13b766f"
---
# Relationship 6468: G0046 — uses → T1608.005

**Source object:** [[01 ATT&CK/G0046 - FIN7|G0046: FIN7]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1608.005 - Link Target|T1608.005: Link Target]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[FIN7](https://attack.mitre.org/groups/G0046) has created a fake link that redirected to an adversary-controlled Dropbox that downloaded the malicious executable.(Citation: BlackBerry_FIN7_April2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--1f3d48af-f6e6-423b-8290-2386f13b766f`.
