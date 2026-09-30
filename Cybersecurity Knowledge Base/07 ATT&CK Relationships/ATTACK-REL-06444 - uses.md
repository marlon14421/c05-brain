---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0579"
target_object: "T1685"
stix_relationship_id: "relationship--f950da7f-1b35-48e5-9209-9fff55c3913f"
---
# Relationship 6444: S0579 — uses → T1685

**Source object:** [[01 ATT&CK/S0579 - Waterbear|S0579: Waterbear]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1685 - Disable or Modify Tools|T1685: Disable or Modify Tools]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Waterbear](https://attack.mitre.org/software/S0579) can hook the ZwOpenProcess and GetExtendedTcpTable APIs called by the process of a security product to hide PIDs and TCP records from detection.(Citation: Trend Micro Waterbear December 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--f950da7f-1b35-48e5-9209-9fff55c3913f`.
