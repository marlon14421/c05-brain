---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0085"
target_object: "T1036.005"
stix_relationship_id: "relationship--11874e26-e692-43da-bb54-760e51a4714f"
---
# Relationship 9663: S0085 — uses → T1036.005

**Source object:** [[01 ATT&CK/S0085 - S-Type|S0085: S-Type]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1036.005 - Match Legitimate Resource Name or Location|T1036.005: Match Legitimate Resource Name or Location]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[S-Type](https://attack.mitre.org/software/S0085) may save itself as a file named `msdtc.exe`, which is also the name of the legitimate Microsoft Distributed Transaction Coordinator service binary.(Citation: Cylance Dust Storm)(Citation: Microsoft DTC)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--11874e26-e692-43da-bb54-760e51a4714f`.
