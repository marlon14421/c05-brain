---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0492"
target_object: "T1518.001"
stix_relationship_id: "relationship--bd17ac4f-746a-4299-b9cc-ff587c57e4f2"
---
# Relationship 5018: S0492 — uses → T1518.001

**Source object:** [[01 ATT&CK/S0492 - CookieMiner|S0492: CookieMiner]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1518.001 - Security Software Discovery|T1518.001: Security Software Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[CookieMiner](https://attack.mitre.org/software/S0492) has checked for the presence of "Little Snitch", macOS network monitoring and application firewall software, stopping and exiting if it is found.(Citation: Unit42 CookieMiner Jan 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--bd17ac4f-746a-4299-b9cc-ff587c57e4f2`.
