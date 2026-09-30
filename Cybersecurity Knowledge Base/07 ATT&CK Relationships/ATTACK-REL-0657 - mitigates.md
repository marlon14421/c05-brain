---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1028"
target_object: "T1556"
stix_relationship_id: "relationship--fc8ef14d-1a07-4f96-85c3-b62ba6bcffc1"
---
# Relationship 0657: M1028 — mitigates → T1556

**Source object:** [[01 ATT&CK/M1028 - Operating System Configuration|M1028: Operating System Configuration]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1556 - Modify Authentication Process|T1556: Modify Authentication Process]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Ensure only valid password filters are registered. Filter DLLs must be present in Windows installation directory (`C:\Windows\System32\` by default) of a domain controller and/or local computer with a corresponding entry in `HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Lsa\Notification Packages`. Starting in Windows 11 22H2, the `EnableMPRNotifications` policy can be disabled through Group Policy or through a configuration service provider to prevent Winlogon from sending credentials to network providers.(Citation: EnableMPRNotifications)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--fc8ef14d-1a07-4f96-85c3-b62ba6bcffc1`.
