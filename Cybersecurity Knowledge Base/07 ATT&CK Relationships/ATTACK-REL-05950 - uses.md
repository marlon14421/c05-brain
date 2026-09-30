---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0046"
target_object: "T1690"
stix_relationship_id: "relationship--b29da7bd-22cf-4a9c-bc2e-caa272641871"
---
# Relationship 5950: C0046 — uses → T1690

**Source object:** [[01 ATT&CK/C0046 - ArcaneDoor|C0046: ArcaneDoor]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1690 - Prevent Command History Logging|T1690: Prevent Command History Logging]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[ArcaneDoor](https://attack.mitre.org/campaigns/C0046) included disabling logging on targeted Cisco ASA appliances.(Citation: Cisco ArcaneDoor 2024)(Citation: CCCS ArcaneDoor 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--b29da7bd-22cf-4a9c-bc2e-caa272641871`.
