---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0060"
target_object: "T1550.003"
stix_relationship_id: "relationship--eb91c7d8-2cfb-4d8b-905a-d146bc8178e2"
---
# Relationship 7173: G0060 — uses → T1550.003

**Source object:** [[01 ATT&CK/G0060 - BRONZE BUTLER|G0060: BRONZE BUTLER]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1550.003 - Pass the Ticket|T1550.003: Pass the Ticket]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[BRONZE BUTLER](https://attack.mitre.org/groups/G0060) has created forged Kerberos Ticket Granting Ticket (TGT) and Ticket Granting Service (TGS) tickets to maintain administrative access.(Citation: Secureworks BRONZE BUTLER Oct 2017)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--eb91c7d8-2cfb-4d8b-905a-d146bc8178e2`.
