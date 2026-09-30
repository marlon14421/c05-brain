---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0376"
target_object: "T1652"
stix_relationship_id: "relationship--04a39f08-17e1-46e8-aba0-db4ef1318ba1"
---
# Relationship 6742: S0376 — uses → T1652

**Source object:** [[01 ATT&CK/S0376 - HOPLIGHT|S0376: HOPLIGHT]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1652 - Device Driver Discovery|T1652: Device Driver Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[HOPLIGHT](https://attack.mitre.org/software/S0376) can enumerate device drivers located in the registry at `HKLM\Software\WBEM\WDM`.(Citation: US-CERT HOPLIGHT Apr 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--04a39f08-17e1-46e8-aba0-db4ef1318ba1`.
