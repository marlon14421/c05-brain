---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0076"
target_object: "T1056.001"
stix_relationship_id: "relationship--bfd49393-75b6-4e67-af74-4bf3c87624b0"
---
# Relationship 5471: S0076 — uses → T1056.001

**Source object:** [[01 ATT&CK/S0076 - FakeM|S0076: FakeM]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1056.001 - Keylogging|T1056.001: Keylogging]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[FakeM](https://attack.mitre.org/software/S0076) contains a keylogger module.(Citation: Scarlet Mimic Jan 2016)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--bfd49393-75b6-4e67-af74-4bf3c87624b0`.
