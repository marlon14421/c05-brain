---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0094"
target_object: "T1518.001"
stix_relationship_id: "relationship--8bfac9d6-8d6d-4a2f-9718-4015f231fdae"
---
# Relationship 2990: G0094 — uses → T1518.001

**Source object:** [[01 ATT&CK/G0094 - Kimsuky|G0094: Kimsuky]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1518.001 - Security Software Discovery|T1518.001: Security Software Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Kimsuky](https://attack.mitre.org/groups/G0094) has checked for the presence of antivirus software with powershell Get-CimInstance -Namespace root/securityCenter2 – classname antivirusproduct .(Citation: KISA Operation Muzabi) [Kimsuky](https://attack.mitre.org/groups/G0094) has also obtained details on antivirus software through WMI queries using `Win32_OperatingSystem` and `SecurityCenter2.AntiVirusProduct`.(Citation: Securonix Kimsuky February 2025) [Kimsuky](https://attack.mitre.org/groups/G0094) has also checked the status of Windows Defender through the use `cmd /s sc query WinDefend`.(Citation: Aryaka Kimsuky July 2025)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--8bfac9d6-8d6d-4a2f-9718-4015f231fdae`.
