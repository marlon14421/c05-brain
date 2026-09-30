---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1037"
target_object: "T1033"
stix_relationship_id: "relationship--7ed13f1b-fa49-4b4e-9bc8-935012710d5f"
---
# Relationship 5607: S1037 — uses → T1033

**Source object:** [[01 ATT&CK/S1037 - STARWHALE|S1037: STARWHALE]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1033 - System Owner-User Discovery|T1033: System Owner/User Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[STARWHALE](https://attack.mitre.org/software/S1037) can gather the username from an infected host.(Citation: Mandiant UNC3313 Feb 2022)(Citation: DHS CISA AA22-055A MuddyWater February 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--7ed13f1b-fa49-4b4e-9bc8-935012710d5f`.
