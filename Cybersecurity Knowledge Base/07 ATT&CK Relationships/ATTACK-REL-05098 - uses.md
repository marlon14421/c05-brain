---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0379"
target_object: "T1082"
stix_relationship_id: "relationship--6765828a-168f-4dd7-8c1b-00f7d98daef5"
---
# Relationship 5098: S0379 — uses → T1082

**Source object:** [[01 ATT&CK/S0379 - Revenge RAT|S0379: Revenge RAT]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1082 - System Information Discovery|T1082: System Information Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Revenge RAT](https://attack.mitre.org/software/S0379) collects the CPU information, OS information, and system language.(Citation: Cylance Shaheen Nov 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--6765828a-168f-4dd7-8c1b-00f7d98daef5`.
