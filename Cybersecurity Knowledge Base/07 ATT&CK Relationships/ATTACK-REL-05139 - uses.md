---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0038"
target_object: "T1114.002"
stix_relationship_id: "relationship--4fdff650-7872-4991-9667-bbe9f88f8085"
---
# Relationship 5139: C0038 — uses → T1114.002

**Source object:** [[01 ATT&CK/C0038 - HomeLand Justice|C0038: HomeLand Justice]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1114.002 - Remote Email Collection|T1114.002: Remote Email Collection]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

During [HomeLand Justice](https://attack.mitre.org/campaigns/C0038), threat actors made multiple HTTP POST requests to the Exchange servers of the victim organization to transfer data.(Citation: CISA Iran Albanian Attacks September 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--4fdff650-7872-4991-9667-bbe9f88f8085`.
