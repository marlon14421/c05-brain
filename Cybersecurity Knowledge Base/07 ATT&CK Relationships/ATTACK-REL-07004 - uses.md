---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0032"
target_object: "T1056.001"
stix_relationship_id: "relationship--becf0a5e-4636-4d2f-bd4a-fd60b15ee74a"
---
# Relationship 7004: S0032 — uses → T1056.001

**Source object:** [[01 ATT&CK/S0032 - gh0st RAT|S0032: gh0st RAT]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1056.001 - Keylogging|T1056.001: Keylogging]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[gh0st RAT](https://attack.mitre.org/software/S0032) has a keylogger.(Citation: Alintanahin 2014)(Citation: Gh0stRAT ATT March 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--becf0a5e-4636-4d2f-bd4a-fd60b15ee74a`.
