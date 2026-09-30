---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0367"
target_object: "T1114"
stix_relationship_id: "relationship--76d0dcb7-046a-40d7-80ec-e0e571359f51"
---
# Relationship 5391: S0367 — uses → T1114

**Source object:** [[01 ATT&CK/S0367 - Emotet|S0367: Emotet]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1114 - Email Collection|T1114: Email Collection]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Emotet](https://attack.mitre.org/software/S0367) has been observed leveraging a module that can scrape email addresses from Outlook.(Citation: CIS Emotet Dec 2018)(Citation: IBM IcedID November 2017)(Citation: Binary Defense Emotes Wi-Fi Spreader)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--76d0dcb7-046a-40d7-80ec-e0e571359f51`.
