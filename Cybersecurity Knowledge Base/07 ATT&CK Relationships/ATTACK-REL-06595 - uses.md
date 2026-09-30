---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0059"
target_object: "T1589.001"
stix_relationship_id: "relationship--078fb58f-0b5b-4021-8467-800893c35d08"
---
# Relationship 6595: G0059 — uses → T1589.001

**Source object:** [[01 ATT&CK/G0059 - Magic Hound|G0059: Magic Hound]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1589.001 - Credentials|T1589.001: Credentials]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Magic Hound](https://attack.mitre.org/groups/G0059) gathered credentials from two victims that they then attempted to validate across 75 different websites. [Magic Hound](https://attack.mitre.org/groups/G0059) has also collected credentials from over 900 Fortinet VPN servers in the US, Europe, and Israel.(Citation: IBM ITG18 2020)(Citation: Microsoft Iranian Threat Actor Trends November 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--078fb58f-0b5b-4021-8467-800893c35d08`.
