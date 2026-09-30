---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0341"
target_object: "T1059.001"
stix_relationship_id: "relationship--8a8068fb-7cf9-4ab6-92a7-e8b3ecdf578d"
---
# Relationship 6002: S0341 — uses → T1059.001

**Source object:** [[01 ATT&CK/S0341 - Xbash|S0341: Xbash]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059.001 - PowerShell|T1059.001: PowerShell]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Xbash](https://attack.mitre.org/software/S0341) can use scripts to invoke PowerShell to download a malicious PE executable or PE DLL for execution.(Citation: Unit42 Xbash Sept 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--8a8068fb-7cf9-4ab6-92a7-e8b3ecdf578d`.
