---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0015"
target_object: "T1566.001"
stix_relationship_id: "relationship--538eb3a4-466e-42d0-9f12-bd9b6de0abe4"
---
# Relationship 8802: C0015 — uses → T1566.001

**Source object:** [[01 ATT&CK/C0015 - C0015|C0015: C0015]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1566.001 - Spearphishing Attachment|T1566.001: Spearphishing Attachment]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

For [C0015](https://attack.mitre.org/campaigns/C0015), security researchers assessed the threat actors likely used a phishing campaign to distribute a weaponized attachment to victims.(Citation: DFIR Conti Bazar Nov 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--538eb3a4-466e-42d0-9f12-bd9b6de0abe4`.
