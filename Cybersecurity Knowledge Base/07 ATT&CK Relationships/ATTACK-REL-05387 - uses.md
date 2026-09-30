---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0007"
target_object: "S1050"
stix_relationship_id: "relationship--f70c842c-f0f4-4b34-afee-87b0fad29cca"
---
# Relationship 5387: C0007 — uses → S1050

**Source object:** [[01 ATT&CK/C0007 - FunnyDream|C0007: FunnyDream]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/S1050 - PcShare|S1050: PcShare]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

During [FunnyDream](https://attack.mitre.org/campaigns/C0007) the threat actors used a customized version of [PcShare](https://attack.mitre.org/software/S1050).(Citation: Bitdefender FunnyDream Campaign November 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--f70c842c-f0f4-4b34-afee-87b0fad29cca`.
