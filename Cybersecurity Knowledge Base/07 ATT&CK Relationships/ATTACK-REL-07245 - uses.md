---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0330"
target_object: "T1614.001"
stix_relationship_id: "relationship--a5cbd480-0147-4e70-9551-03a2b5b8fdcb"
---
# Relationship 7245: S0330 — uses → T1614.001

**Source object:** [[01 ATT&CK/S0330 - Zeus Panda|S0330: Zeus Panda]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1614.001 - System Language Discovery|T1614.001: System Language Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Zeus Panda](https://attack.mitre.org/software/S0330) queries the system's keyboard mapping to determine the language used on the system. It will terminate execution if it detects LANG_RUSSIAN, LANG_BELARUSIAN, LANG_KAZAK, or LANG_UKRAINIAN.(Citation: Talos Zeus Panda Nov 2017)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--a5cbd480-0147-4e70-9551-03a2b5b8fdcb`.
