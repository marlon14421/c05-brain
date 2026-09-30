---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0477"
target_object: "T1574.001"
stix_relationship_id: "relationship--cbf9284f-2f47-4d1f-b708-861b0e1e85b5"
---
# Relationship 6377: S0477 — uses → T1574.001

**Source object:** [[01 ATT&CK/S0477 - Goopy|S0477: Goopy]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1574.001 - DLL|T1574.001: DLL]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Goopy](https://attack.mitre.org/software/S0477) has the ability to side-load malicious DLLs with legitimate applications from Kaspersky, Microsoft, and Google.(Citation: Cybereason Cobalt Kitty 2017)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--cbf9284f-2f47-4d1f-b708-861b0e1e85b5`.
