---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0015"
target_object: "T1069.001"
stix_relationship_id: "relationship--5968f7a6-a300-4a1b-9a4e-655e9300392b"
---
# Relationship 6366: C0015 — uses → T1069.001

**Source object:** [[01 ATT&CK/C0015 - C0015|C0015: C0015]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1069.001 - Local Groups|T1069.001: Local Groups]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

During [C0015](https://attack.mitre.org/campaigns/C0015), the threat actors used the command `net localgroup "adminstrator" ` to identify accounts with local administrator rights.(Citation: DFIR Conti Bazar Nov 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--5968f7a6-a300-4a1b-9a4e-655e9300392b`.
