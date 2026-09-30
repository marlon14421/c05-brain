---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1070"
target_object: "T1106"
stix_relationship_id: "relationship--d10cea20-846f-4c55-9566-cd7367ae6488"
---
# Relationship 5176: S1070 — uses → T1106

**Source object:** [[01 ATT&CK/S1070 - Black Basta|S1070: Black Basta]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1106 - Native API|T1106: Native API]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Black Basta](https://attack.mitre.org/software/S1070) has the ability to use native APIs for numerous functions including discovery and defense evasion.(Citation: Minerva Labs Black Basta May 2022)(Citation: Cyble Black Basta May 2022)(Citation: Avertium Black Basta June 2022)(Citation: Check Point Black Basta October 2022)(Citation: Trend Micro Black Basta May 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--d10cea20-846f-4c55-9566-cd7367ae6488`.
