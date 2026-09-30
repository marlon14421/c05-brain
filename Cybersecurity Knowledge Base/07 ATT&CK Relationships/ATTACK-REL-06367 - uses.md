---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0575"
target_object: "T1057"
stix_relationship_id: "relationship--eacc205b-b8f9-4427-b8bd-3eba5a5a6179"
---
# Relationship 6367: S0575 — uses → T1057

**Source object:** [[01 ATT&CK/S0575 - Conti|S0575: Conti]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1057 - Process Discovery|T1057: Process Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Conti](https://attack.mitre.org/software/S0575) can enumerate through all open processes to search for any that have the string “sql” in their process name.(Citation: CarbonBlack Conti July 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--eacc205b-b8f9-4427-b8bd-3eba5a5a6179`.
