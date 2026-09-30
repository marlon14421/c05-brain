---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0242"
target_object: "T1614.001"
stix_relationship_id: "relationship--cfed60a3-c288-4c12-bfe2-2c0234a3cfa7"
---
# Relationship 6729: S0242 — uses → T1614.001

**Source object:** [[01 ATT&CK/S0242 - SynAck|S0242: SynAck]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1614.001 - System Language Discovery|T1614.001: System Language Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[SynAck](https://attack.mitre.org/software/S0242) lists all the keyboard layouts installed on the victim’s system using GetKeyboardLayoutList API and checks against a hardcoded language code list. If a match if found, SynAck sleeps for 300 seconds and then exits without encrypting files.(Citation: SecureList SynAck Doppelgänging May 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--cfed60a3-c288-4c12-bfe2-2c0234a3cfa7`.
