---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0386"
target_object: "T1041"
stix_relationship_id: "relationship--42de94e7-86f3-41d9-9e01-45fff8be1451"
---
# Relationship 7624: S0386 — uses → T1041

**Source object:** [[01 ATT&CK/S0386 - Ursnif|S0386: Ursnif]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1041 - Exfiltration Over C2 Channel|T1041: Exfiltration Over C2 Channel]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Ursnif](https://attack.mitre.org/software/S0386) has used HTTP POSTs to exfil gathered information.(Citation: TrendMicro Ursnif Mar 2015)(Citation: FireEye Ursnif Nov 2017)(Citation: ProofPoint Ursnif Aug 2016)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--42de94e7-86f3-41d9-9e01-45fff8be1451`.
