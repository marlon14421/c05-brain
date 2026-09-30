---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0607"
target_object: "T1134"
stix_relationship_id: "relationship--d84bda97-a8d5-4886-8172-c5a794b681af"
---
# Relationship 6262: S0607 — uses → T1134

**Source object:** [[01 ATT&CK/S0607 - KillDisk|S0607: KillDisk]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1134 - Access Token Manipulation|T1134: Access Token Manipulation]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[KillDisk](https://attack.mitre.org/software/S0607) has attempted to get the access token of a process by calling OpenProcessToken . If [KillDisk](https://attack.mitre.org/software/S0607) gets the access token, then it attempt to modify the token privileges with AdjustTokenPrivileges .(Citation: Trend Micro KillDisk 2)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--d84bda97-a8d5-4886-8172-c5a794b681af`.
