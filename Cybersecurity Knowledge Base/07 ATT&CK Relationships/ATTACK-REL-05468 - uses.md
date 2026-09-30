---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0136"
target_object: "T1025"
stix_relationship_id: "relationship--00ae99d1-db02-4007-8669-04d7fc4c1390"
---
# Relationship 5468: S0136 — uses → T1025

**Source object:** [[01 ATT&CK/S0136 - USBStealer|S0136: USBStealer]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1025 - Data from Removable Media|T1025: Data from Removable Media]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

Once a removable media device is inserted back into the first victim, [USBStealer](https://attack.mitre.org/software/S0136) collects data from it that was exfiltrated from a second victim.(Citation: ESET Sednit USBStealer 2014)(Citation: Kaspersky Sofacy)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--00ae99d1-db02-4007-8669-04d7fc4c1390`.
