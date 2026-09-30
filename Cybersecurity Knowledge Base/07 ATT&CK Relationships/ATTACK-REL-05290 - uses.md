---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0059"
target_object: "T1082"
stix_relationship_id: "relationship--2e367a09-1d94-4ea4-984c-a592b769fffa"
---
# Relationship 5290: S0059 — uses → T1082

**Source object:** [[01 ATT&CK/S0059 - WinMM|S0059: WinMM]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1082 - System Information Discovery|T1082: System Information Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[WinMM](https://attack.mitre.org/software/S0059) collects the system name, OS version including service pack, and system install date and sends the information to the C2 server.(Citation: Baumgartner Naikon 2015)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--2e367a09-1d94-4ea4-984c-a592b769fffa`.
