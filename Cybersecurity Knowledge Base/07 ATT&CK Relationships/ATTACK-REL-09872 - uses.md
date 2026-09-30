---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0052"
target_object: "T1560.003"
stix_relationship_id: "relationship--292b2a10-ebee-4fbb-b359-2eee16aa46ba"
---
# Relationship 9872: G0052 — uses → T1560.003

**Source object:** [[01 ATT&CK/G0052 - CopyKittens|G0052: CopyKittens]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1560.003 - Archive via Custom Method|T1560.003: Archive via Custom Method]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[CopyKittens](https://attack.mitre.org/groups/G0052) encrypts data with a substitute cipher prior to exfiltration.(Citation: CopyKittens Nov 2015)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--292b2a10-ebee-4fbb-b359-2eee16aa46ba`.
