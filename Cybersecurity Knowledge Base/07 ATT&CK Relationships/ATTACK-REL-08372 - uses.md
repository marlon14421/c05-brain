---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0633"
target_object: "T1071.004"
stix_relationship_id: "relationship--73ddd025-b313-49cc-8a28-4c3869eb5a16"
---
# Relationship 8372: S0633 — uses → T1071.004

**Source object:** [[01 ATT&CK/S0633 - Sliver|S0633: Sliver]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1071.004 - DNS|T1071.004: DNS]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Sliver](https://attack.mitre.org/software/S0633) can support C2 communications over DNS.(Citation: Cybersecurity Advisory SVR TTP May 2021)(Citation: Bishop Fox Sliver Framework August 2019)(Citation: GitHub Sliver C2 DNS)(Citation: Cybereason Sliver Undated)(Citation: Microsoft Sliver 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--73ddd025-b313-49cc-8a28-4c3869eb5a16`.
