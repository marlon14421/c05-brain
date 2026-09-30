---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0102"
target_object: "T1112"
stix_relationship_id: "relationship--75f0ea4c-5b88-4b14-9859-67379f4ba9b0"
---
# Relationship 5067: G0102 — uses → T1112

**Source object:** [[01 ATT&CK/G0102 - Wizard Spider|G0102: Wizard Spider]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1112 - Modify Registry|T1112: Modify Registry]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Wizard Spider](https://attack.mitre.org/groups/G0102) has modified the Registry key HKLM\System\CurrentControlSet\Control\SecurityProviders\WDigest by setting the UseLogonCredential registry value to 1 in order to force credentials to be stored in clear text in memory. [Wizard Spider](https://attack.mitre.org/groups/G0102) has also modified the WDigest registry key to allow plaintext credentials to be cached in memory.(Citation: CrowdStrike Grim Spider May 2019)(Citation: Mandiant FIN12 Oct 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--75f0ea4c-5b88-4b14-9859-67379f4ba9b0`.
