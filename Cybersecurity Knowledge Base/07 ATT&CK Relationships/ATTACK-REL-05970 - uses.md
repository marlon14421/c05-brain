---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0026"
target_object: "T1078"
stix_relationship_id: "relationship--1ac5bace-cdc2-4a1b-abad-d30ca0ed7f45"
---
# Relationship 5970: G0026 — uses → T1078

**Source object:** [[01 ATT&CK/G0026 - APT18|G0026: APT18]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1078 - Valid Accounts|T1078: Valid Accounts]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[APT18](https://attack.mitre.org/groups/G0026) actors leverage legitimate credentials to log into external remote services.(Citation: RSA2017 Detect and Respond Adair)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--1ac5bace-cdc2-4a1b-abad-d30ca0ed7f45`.
