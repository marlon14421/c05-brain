---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0492"
target_object: "T1555.003"
stix_relationship_id: "relationship--19bfa4e1-509b-417a-9bcc-b739f7d798a7"
---
# Relationship 6473: S0492 — uses → T1555.003

**Source object:** [[01 ATT&CK/S0492 - CookieMiner|S0492: CookieMiner]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1555.003 - Credentials from Web Browsers|T1555.003: Credentials from Web Browsers]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[CookieMiner](https://attack.mitre.org/software/S0492) can steal saved usernames and passwords in Chrome as well as credit card credentials.(Citation: Unit42 CookieMiner Jan 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--19bfa4e1-509b-417a-9bcc-b739f7d798a7`.
