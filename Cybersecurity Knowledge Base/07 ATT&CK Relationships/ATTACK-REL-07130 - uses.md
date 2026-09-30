---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0194"
target_object: "T1552.002"
stix_relationship_id: "relationship--216b3711-fc70-4029-aaec-a8f021c38bef"
---
# Relationship 7130: S0194 — uses → T1552.002

**Source object:** [[01 ATT&CK/S0194 - PowerSploit|S0194: PowerSploit]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1552.002 - Credentials in Registry|T1552.002: Credentials in Registry]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[PowerSploit](https://attack.mitre.org/software/S0194) has several modules that search the Windows Registry for stored credentials: Get-UnattendedInstallFile , Get-Webconfig , Get-ApplicationHost , Get-SiteListPassword , Get-CachedGPPPassword , and Get-RegistryAutoLogon .(Citation: Pentestlab Stored Credentials)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--216b3711-fc70-4029-aaec-a8f021c38bef`.
