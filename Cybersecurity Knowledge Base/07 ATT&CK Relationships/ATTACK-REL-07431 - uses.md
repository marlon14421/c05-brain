---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0690"
target_object: "T1555.001"
stix_relationship_id: "relationship--46970d57-04cb-4ffb-9c7e-ff66c0811f25"
---
# Relationship 7431: S0690 — uses → T1555.001

**Source object:** [[01 ATT&CK/S0690 - Green Lambert|S0690: Green Lambert]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1555.001 - Keychain|T1555.001: Keychain]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Green Lambert](https://attack.mitre.org/software/S0690) can use Keychain Services API functions to find and collect passwords, such as `SecKeychainFindInternetPassword` and `SecKeychainItemCopyAttributesAndData`.(Citation: Objective See Green Lambert for OSX Oct 2021)(Citation: Glitch-Cat Green Lambert ATTCK Oct 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--46970d57-04cb-4ffb-9c7e-ff66c0811f25`.
