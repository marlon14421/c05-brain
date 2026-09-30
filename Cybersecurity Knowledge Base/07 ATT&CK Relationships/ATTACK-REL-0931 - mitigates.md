---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1052"
target_object: "T1574.005"
stix_relationship_id: "relationship--681ea412-54a2-4580-960f-98e1219fff1f"
---
# Relationship 0931: M1052 — mitigates → T1574.005

**Source object:** [[01 ATT&CK/M1052 - User Account Control|M1052: User Account Control]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1574.005 - Executable Installer File Permissions Weakness|T1574.005: Executable Installer File Permissions Weakness]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Turn off UAC's privilege elevation for standard users [HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Policies\System] to automatically deny elevation requests, add: "ConsentPromptBehaviorUser"=dword:00000000 . Consider enabling installer detection for all users by adding: "EnableInstallerDetection"=dword:00000001 . This will prompt for a password for installation and also log the attempt. To disable installer detection, instead add: "EnableInstallerDetection"=dword:00000000 . This may prevent potential elevation of privileges through exploitation during the process of UAC detecting the installer, but will allow the installation process to continue without being logged. (Citation: Executable Installers are Vulnerable)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--681ea412-54a2-4580-960f-98e1219fff1f`.
