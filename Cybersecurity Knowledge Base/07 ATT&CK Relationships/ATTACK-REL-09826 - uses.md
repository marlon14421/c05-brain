---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0606"
target_object: "T1218.011"
stix_relationship_id: "relationship--849e3f46-81a5-4865-9a14-fbbf67bfd00a"
---
# Relationship 9826: S0606 — uses → T1218.011

**Source object:** [[01 ATT&CK/S0606 - Bad Rabbit|S0606: Bad Rabbit]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1218.011 - Rundll32|T1218.011: Rundll32]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Bad Rabbit](https://attack.mitre.org/software/S0606) has used rundll32 to launch a malicious DLL as C:Windowsinfpub.dat .(Citation: Secure List Bad Rabbit)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--849e3f46-81a5-4865-9a14-fbbf67bfd00a`.
