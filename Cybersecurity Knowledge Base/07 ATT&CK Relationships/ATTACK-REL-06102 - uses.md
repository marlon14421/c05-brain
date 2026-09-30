---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1066"
target_object: "T1566.001"
stix_relationship_id: "relationship--1813df9f-2bd9-4451-b4dd-aa80716ce151"
---
# Relationship 6102: S1066 — uses → T1566.001

**Source object:** [[01 ATT&CK/S1066 - DarkTortilla|S1066: DarkTortilla]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1566.001 - Spearphishing Attachment|T1566.001: Spearphishing Attachment]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[DarkTortilla](https://attack.mitre.org/software/S1066) has been distributed via spearphishing emails containing archive attachments, with file types such as .iso, .zip, .img, .dmg, and .tar, as well as through malicious documents.(Citation: Secureworks DarkTortilla Aug 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--1813df9f-2bd9-4451-b4dd-aa80716ce151`.
