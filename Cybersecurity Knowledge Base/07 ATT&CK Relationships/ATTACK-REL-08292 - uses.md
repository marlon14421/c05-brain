---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0089"
target_object: "T1518.001"
stix_relationship_id: "relationship--2a8c6029-7714-437a-87a2-bc91067575e6"
---
# Relationship 8292: G0089 — uses → T1518.001

**Source object:** [[01 ATT&CK/G0089 - The White Company|G0089: The White Company]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1518.001 - Security Software Discovery|T1518.001: Security Software Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[The White Company](https://attack.mitre.org/groups/G0089) has checked for specific antivirus products on the target’s computer, including Kaspersky, Quick Heal, AVG, BitDefender, Avira, Sophos, Avast!, and ESET.(Citation: Cylance Shaheen Nov 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--2a8c6029-7714-437a-87a2-bc91067575e6`.
