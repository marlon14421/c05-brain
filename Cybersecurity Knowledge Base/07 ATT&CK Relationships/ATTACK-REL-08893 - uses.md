---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0098"
target_object: "T1546.010"
stix_relationship_id: "relationship--3d16b34f-f58b-4469-a0ef-7585f88d6001"
---
# Relationship 8893: S0098 — uses → T1546.010

**Source object:** [[01 ATT&CK/S0098 - T9000|S0098: T9000]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1546.010 - AppInit DLLs|T1546.010: AppInit DLLs]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

If a victim meets certain criteria, [T9000](https://attack.mitre.org/software/S0098) uses the AppInit_DLL functionality to achieve persistence by ensuring that every user mode process that is spawned will load its malicious DLL, ResN32.dll. It does this by creating the following Registry keys: HKLM\Software\Microsoft\Windows NT\CurrentVersion\Windows\AppInit_DLLs – %APPDATA%\Intel\ResN32.dll and HKLM\Software\Microsoft\Windows NT\CurrentVersion\Windows\LoadAppInit_DLLs – 0x1 .(Citation: Palo Alto T9000 Feb 2016)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--3d16b34f-f58b-4469-a0ef-7585f88d6001`.
