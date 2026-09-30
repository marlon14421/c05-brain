---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0136"
target_object: "T1074.001"
stix_relationship_id: "relationship--fe229513-0cd9-4e9a-a333-2748ef03dfbc"
---
# Relationship 6297: S0136 — uses → T1074.001

**Source object:** [[01 ATT&CK/S0136 - USBStealer|S0136: USBStealer]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1074.001 - Local Data Staging|T1074.001: Local Data Staging]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[USBStealer](https://attack.mitre.org/software/S0136) collects files matching certain criteria from the victim and stores them in a local directory for later exfiltration.(Citation: ESET Sednit USBStealer 2014)(Citation: Kaspersky Sofacy)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--fe229513-0cd9-4e9a-a333-2748ef03dfbc`.
