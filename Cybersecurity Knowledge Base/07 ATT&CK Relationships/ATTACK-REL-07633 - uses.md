---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0386"
target_object: "T1055.005"
stix_relationship_id: "relationship--6e8621ee-9a1f-4a61-86f4-aae3c3d20d0c"
---
# Relationship 7633: S0386 — uses → T1055.005

**Source object:** [[01 ATT&CK/S0386 - Ursnif|S0386: Ursnif]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1055.005 - Thread Local Storage|T1055.005: Thread Local Storage]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Ursnif](https://attack.mitre.org/software/S0386) has injected code into target processes via thread local storage callbacks.(Citation: TrendMicro Ursnif Mar 2015)(Citation: TrendMicro PE_URSNIF.A2)(Citation: FireEye Ursnif Nov 2017)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--6e8621ee-9a1f-4a61-86f4-aae3c3d20d0c`.
