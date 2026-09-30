---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0531"
target_object: "T1106"
stix_relationship_id: "relationship--d06c864f-e4b8-484d-8e75-76a480509665"
---
# Relationship 6583: S0531 — uses → T1106

**Source object:** [[01 ATT&CK/S0531 - Grandoreiro|S0531: Grandoreiro]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1106 - Native API|T1106: Native API]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Grandoreiro](https://attack.mitre.org/software/S0531) can execute through the WinExec API.(Citation: ESET Grandoreiro April 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--d06c864f-e4b8-484d-8e75-76a480509665`.
