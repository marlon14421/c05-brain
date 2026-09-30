---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0670"
target_object: "T1056.001"
stix_relationship_id: "relationship--0b3b2d98-213c-487f-b526-9336c2ed4555"
---
# Relationship 5982: S0670 — uses → T1056.001

**Source object:** [[01 ATT&CK/S0670 - WarzoneRAT|S0670: WarzoneRAT]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1056.001 - Keylogging|T1056.001: Keylogging]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[WarzoneRAT](https://attack.mitre.org/software/S0670) has the capability to install a live and offline keylogger, including through the use of the `GetAsyncKeyState` Windows API.(Citation: Check Point Warzone Feb 2020)(Citation: Uptycs Warzone UAC Bypass November 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--0b3b2d98-213c-487f-b526-9336c2ed4555`.
