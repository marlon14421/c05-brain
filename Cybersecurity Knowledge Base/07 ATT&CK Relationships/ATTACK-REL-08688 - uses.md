---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S9043"
target_object: "T1485"
stix_relationship_id: "relationship--cbca9348-6e7b-49bd-88f5-66b0ec02e5d0"
---
# Relationship 8688: S9043 — uses → T1485

**Source object:** [[01 ATT&CK/S9043 - Mini Shai-Hulud|S9043: Mini Shai-Hulud]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1485 - Data Destruction|T1485: Data Destruction]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Mini Shai-Hulud](https://attack.mitre.org/software/S9043) has wiped data on devices that fall within specified parameters to include those that resolve to specific geolocations including Iran and Israel.(Citation: Hunt.io TeamPCP Toolkit MAY 2026)(Citation: Phoenix TeamPCP 20 MAY 2026) [Mini Shai-Hulud](https://attack.mitre.org/software/S9043) has also implemented a dead-man’s switch that wipes the victims home directory if the operator revokes a GitHub token created by the adversary. (Citation: Flashpoint Mini Shai-Hulud MAY 2026)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--cbca9348-6e7b-49bd-88f5-66b0ec02e5d0`.
