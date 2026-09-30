---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0052"
target_object: "T1564.003"
stix_relationship_id: "relationship--948a5d37-65d1-403f-99bb-0f08186aeebc"
---
# Relationship 6504: G0052 — uses → T1564.003

**Source object:** [[01 ATT&CK/G0052 - CopyKittens|G0052: CopyKittens]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1564.003 - Hidden Window|T1564.003: Hidden Window]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[CopyKittens](https://attack.mitre.org/groups/G0052) has used -w hidden and -windowstyle hidden to conceal [PowerShell](https://attack.mitre.org/techniques/T1059/001) windows. (Citation: ClearSky Wilted Tulip July 2017)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--948a5d37-65d1-403f-99bb-0f08186aeebc`.
