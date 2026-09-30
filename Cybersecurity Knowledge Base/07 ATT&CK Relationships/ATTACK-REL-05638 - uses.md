---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0624"
target_object: "T1553.002"
stix_relationship_id: "relationship--c7e92a33-f627-44bd-80be-d6e0cfcef656"
---
# Relationship 5638: S0624 — uses → T1553.002

**Source object:** [[01 ATT&CK/S0624 - Ecipekac|S0624: Ecipekac]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1553.002 - Code Signing|T1553.002: Code Signing]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Ecipekac](https://attack.mitre.org/software/S0624) has used a valid, legitimate digital signature to evade detection.(Citation: Securelist APT10 March 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c7e92a33-f627-44bd-80be-d6e0cfcef656`.
