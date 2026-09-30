---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0375"
target_object: "T1547.004"
stix_relationship_id: "relationship--9cae28f1-dbae-406b-b205-ab9c9cbd26f5"
---
# Relationship 6947: S0375 — uses → T1547.004

**Source object:** [[01 ATT&CK/S0375 - Remexi|S0375: Remexi]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1547.004 - Winlogon Helper DLL|T1547.004: Winlogon Helper DLL]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Remexi](https://attack.mitre.org/software/S0375) achieves persistence using Userinit by adding the Registry key HKLM\Software\Microsoft\Windows NT\CurrentVersion\Winlogon\Userinit .(Citation: Securelist Remexi Jan 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--9cae28f1-dbae-406b-b205-ab9c9cbd26f5`.
