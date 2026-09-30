---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1146"
target_object: "T1482"
stix_relationship_id: "relationship--79ad0030-3301-4063-866f-4947531ff8c0"
---
# Relationship 7277: S1146 — uses → T1482

**Source object:** [[01 ATT&CK/S1146 - MgBot|S1146: MgBot]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1482 - Domain Trust Discovery|T1482: Domain Trust Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[MgBot](https://attack.mitre.org/software/S1146) includes modules for collecting information on local domain users and permissions.(Citation: Symantec Daggerfly 2023)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--79ad0030-3301-4063-866f-4947531ff8c0`.
