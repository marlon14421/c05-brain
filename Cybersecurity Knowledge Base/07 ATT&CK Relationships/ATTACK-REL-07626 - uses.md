---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0148"
target_object: "T1548.002"
stix_relationship_id: "relationship--0d0b4507-b600-41f1-be98-03909e5d99cf"
---
# Relationship 7626: S0148 — uses → T1548.002

**Source object:** [[01 ATT&CK/S0148 - RTM|S0148: RTM]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1548.002 - Bypass User Account Control|T1548.002: Bypass User Account Control]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[RTM](https://attack.mitre.org/software/S0148) can attempt to run the program as admin, then show a fake error message and a legitimate UAC bypass prompt to the user in an attempt to socially engineer the user into escalating privileges.(Citation: ESET RTM Feb 2017)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--0d0b4507-b600-41f1-be98-03909e5d99cf`.
