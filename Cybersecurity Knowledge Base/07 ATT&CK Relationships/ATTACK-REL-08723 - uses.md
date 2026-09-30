---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0064"
target_object: "T1059.001"
stix_relationship_id: "relationship--cd69ba48-b716-4278-b1a0-2efd3bd2d4de"
---
# Relationship 8723: G0064 — uses → T1059.001

**Source object:** [[01 ATT&CK/G0064 - APT33|G0064: APT33]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059.001 - PowerShell|T1059.001: PowerShell]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[APT33](https://attack.mitre.org/groups/G0064) has utilized PowerShell to download files from the C2 server and run various scripts. (Citation: Symantec Elfin Mar 2019)(Citation: Microsoft Holmium June 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--cd69ba48-b716-4278-b1a0-2efd3bd2d4de`.
