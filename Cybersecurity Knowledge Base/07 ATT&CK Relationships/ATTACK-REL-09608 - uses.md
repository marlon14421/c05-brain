---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1130"
target_object: "T1218.011"
stix_relationship_id: "relationship--9ad1d50a-31b2-4fc6-ac22-f83f68e97a15"
---
# Relationship 9608: S1130 — uses → T1218.011

**Source object:** [[01 ATT&CK/S1130 - Raspberry Robin|S1130: Raspberry Robin]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1218.011 - Rundll32|T1218.011: Rundll32]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Raspberry Robin](https://attack.mitre.org/software/S1130) uses rundll32 execution without any command line parameters to contact command and control infrastructure, such as IP addresses associated with [Tor](https://attack.mitre.org/software/S0183) nodes.(Citation: RedCanary RaspberryRobin 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--9ad1d50a-31b2-4fc6-ac22-f83f68e97a15`.
