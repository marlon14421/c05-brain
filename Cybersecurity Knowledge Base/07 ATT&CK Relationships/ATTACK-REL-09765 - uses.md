---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0127"
target_object: "T1566.001"
stix_relationship_id: "relationship--5d881746-44f9-4865-86de-97253fc197fb"
---
# Relationship 9765: G0127 — uses → T1566.001

**Source object:** [[01 ATT&CK/G0127 - TA551|G0127: TA551]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1566.001 - Spearphishing Attachment|T1566.001: Spearphishing Attachment]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[TA551](https://attack.mitre.org/groups/G0127) has sent spearphishing attachments with password protected ZIP files.(Citation: Unit 42 Valak July 2020)(Citation: Unit 42 TA551 Jan 2021)(Citation: Secureworks GOLD CABIN)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--5d881746-44f9-4865-86de-97253fc197fb`.
