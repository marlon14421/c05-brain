---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0081"
target_object: "T1547.001"
stix_relationship_id: "relationship--f696324d-7fb4-44ca-82dd-3385b55fbb80"
---
# Relationship 9194: S0081 — uses → T1547.001

**Source object:** [[01 ATT&CK/S0081 - Elise|S0081: Elise]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1547.001 - Registry Run Keys - Startup Folder|T1547.001: Registry Run Keys / Startup Folder]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

If establishing persistence by installation as a new service fails, one variant of [Elise](https://attack.mitre.org/software/S0081) establishes persistence for the created .exe file by setting the following Registry key: HKCU\Software\Microsoft\Windows\CurrentVersion\Run\svchost : %APPDATA%\Microsoft\Network\svchost.exe . Other variants have set the following Registry keys for persistence: HKCU\Software\Microsoft\Windows\CurrentVersion\Run\imejp : [self] and HKCU\Software\Microsoft\Windows\CurrentVersion\Run\IAStorD .(Citation: Lotus Blossom Jun 2015)(Citation: Accenture Dragonfish Jan 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--f696324d-7fb4-44ca-82dd-3385b55fbb80`.
