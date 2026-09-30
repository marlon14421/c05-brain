---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1024"
target_object: "T1560.001"
stix_relationship_id: "relationship--f7416b2f-b3b3-4fc4-a463-05ae302a6b24"
---
# Relationship 8119: G1024 — uses → T1560.001

**Source object:** [[01 ATT&CK/G1024 - Akira|G1024: Akira]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1560.001 - Archive via Utility|T1560.001: Archive via Utility]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Akira](https://attack.mitre.org/groups/G1024) uses utilities such as WinRAR to archive data prior to exfiltration.(Citation: Secureworks GOLD SAHARA)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--f7416b2f-b3b3-4fc4-a463-05ae302a6b24`.
