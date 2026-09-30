---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1016"
target_object: "T1056.001"
stix_relationship_id: "relationship--b5a39593-27ad-44dc-99f9-fcadc6d464ed"
---
# Relationship 8954: S1016 — uses → T1056.001

**Source object:** [[01 ATT&CK/S1016 - MacMa|S1016: MacMa]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1056.001 - Keylogging|T1056.001: Keylogging]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[MacMa](https://attack.mitre.org/software/S1016) can use Core Graphics Event Taps to intercept user keystrokes from any text input field and saves them to text files. Text input fields include Spotlight, Finder, Safari, Mail, Messages, and other apps that have text fields for passwords.(Citation: Objective-See MacMa Nov 2021)(Citation: SentinelOne MacMa Nov 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--b5a39593-27ad-44dc-99f9-fcadc6d464ed`.
