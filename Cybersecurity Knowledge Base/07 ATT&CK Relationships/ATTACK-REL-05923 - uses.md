---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0640"
target_object: "T1057"
stix_relationship_id: "relationship--5b37bd8c-d5a6-4564-a110-bb515ff9f78c"
---
# Relationship 5923: S0640 — uses → T1057

**Source object:** [[01 ATT&CK/S0640 - Avaddon|S0640: Avaddon]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1057 - Process Discovery|T1057: Process Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Avaddon](https://attack.mitre.org/software/S0640) has collected information about running processes.(Citation: Arxiv Avaddon Feb 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--5b37bd8c-d5a6-4564-a110-bb515ff9f78c`.
