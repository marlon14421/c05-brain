---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0007"
target_object: "T1018"
stix_relationship_id: "relationship--3d4cb0b5-148f-4e3f-a09f-7a17823b2b56"
---
# Relationship 7403: C0007 — uses → T1018

**Source object:** [[01 ATT&CK/C0007 - FunnyDream|C0007: FunnyDream]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1018 - Remote System Discovery|T1018: Remote System Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

During [FunnyDream](https://attack.mitre.org/campaigns/C0007), the threat actors used several tools and batch files to map victims' internal networks.(Citation: Bitdefender FunnyDream Campaign November 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--3d4cb0b5-148f-4e3f-a09f-7a17823b2b56`.
