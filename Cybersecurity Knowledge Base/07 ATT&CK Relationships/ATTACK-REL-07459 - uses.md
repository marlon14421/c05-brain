---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1004"
target_object: "T1598.004"
stix_relationship_id: "relationship--60fc3c88-bff5-4a06-88f3-15715e4cafda"
---
# Relationship 7459: G1004 — uses → T1598.004

**Source object:** [[01 ATT&CK/G1004 - LAPSUS$|G1004: LAPSUS$]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1598.004 - Spearphishing Voice|T1598.004: Spearphishing Voice]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[LAPSUS$](https://attack.mitre.org/groups/G1004) has called victims' help desk to convince the support personnel to reset a privileged account’s credentials.(Citation: MSTIC DEV-0537 Mar 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--60fc3c88-bff5-4a06-88f3-15715e4cafda`.
