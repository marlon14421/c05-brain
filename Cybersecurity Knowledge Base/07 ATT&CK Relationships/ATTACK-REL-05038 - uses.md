---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0229"
target_object: "T1218.010"
stix_relationship_id: "relationship--18d4782f-0e33-4bf5-b0a2-8dc04cacb617"
---
# Relationship 5038: S0229 — uses → T1218.010

**Source object:** [[01 ATT&CK/S0229 - Orz|S0229: Orz]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1218.010 - Regsvr32|T1218.010: Regsvr32]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

Some [Orz](https://attack.mitre.org/software/S0229) versions have an embedded DLL known as MockDll that uses [Process Hollowing](https://attack.mitre.org/techniques/T1055/012) and regsvr32 to execute another payload.(Citation: Proofpoint Leviathan Oct 2017)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--18d4782f-0e33-4bf5-b0a2-8dc04cacb617`.
