---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S9032"
target_object: "T1547.001"
stix_relationship_id: "relationship--e888ca4d-7970-4f35-a7f1-a2f9a14b2f22"
---
# Relationship 6372: S9032 — uses → T1547.001

**Source object:** [[01 ATT&CK/S9032 - MuddyViper|S9032: MuddyViper]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1547.001 - Registry Run Keys - Startup Folder|T1547.001: Registry Run Keys / Startup Folder]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[MuddyViper](https://attack.mitre.org/software/S9032) has the ability to establish persistence by configuring its installation directory as a Windows Startup folder by setting the following Registry values to `%APPDATALOCAL%\Microsoft\Windows\PPBCompatCache\ManagerCache`: `HKCU\Software\Microsoft\Windows\CurrentVersion\Explorer\User Shell Folders\Startup` and `HKCU\Software\Microsoft\Windows\CurrentVersion\Explorer\Shell Folders\Startup`.(Citation: ESET_MuddyWater_Dec2025)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e888ca4d-7970-4f35-a7f1-a2f9a14b2f22`.
