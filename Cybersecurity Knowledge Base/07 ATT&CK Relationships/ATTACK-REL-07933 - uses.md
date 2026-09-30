---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1111"
target_object: "T1574.007"
stix_relationship_id: "relationship--c33b6ac0-213a-46a0-8eef-5d287f0c7676"
---
# Relationship 7933: S1111 — uses → T1574.007

**Source object:** [[01 ATT&CK/S1111 - DarkGate|S1111: DarkGate]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1574.007 - Path Interception by PATH Environment Variable|T1574.007: Path Interception by PATH Environment Variable]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[DarkGate](https://attack.mitre.org/software/S1111) overrides the %windir% environment variable by setting a Registry key, HKEY_CURRENT_User\Environment\windir , to an alternate command to execute a malicious AutoIt script. This allows [DarkGate](https://attack.mitre.org/software/S1111) to run every time the scheduled task DiskCleanup is executed as this uses the path value %windir%\system32\cleanmgr.exe for execution.(Citation: Ensilo Darkgate 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c33b6ac0-213a-46a0-8eef-5d287f0c7676`.
