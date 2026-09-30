---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1142"
target_object: "T1137.006"
stix_relationship_id: "relationship--f8c0613b-557e-4a9d-9f01-d57138d18c24"
---
# Relationship 9792: S1142 — uses → T1137.006

**Source object:** [[01 ATT&CK/S1142 - LunarMail|S1142: LunarMail]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1137.006 - Add-ins|T1137.006: Add-ins]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[LunarMail](https://attack.mitre.org/software/S1142) has the ability to use Outlook add-ins for persistence.(Citation: ESET Turla Lunar toolset May 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--f8c0613b-557e-4a9d-9f01-d57138d18c24`.
