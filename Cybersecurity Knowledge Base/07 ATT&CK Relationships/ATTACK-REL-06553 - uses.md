---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0410"
target_object: "T1082"
stix_relationship_id: "relationship--834bbbc7-33b7-41e4-9bc8-98401a5a0e36"
---
# Relationship 6553: S0410 — uses → T1082

**Source object:** [[01 ATT&CK/S0410 - Fysbis|S0410: Fysbis]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1082 - System Information Discovery|T1082: System Information Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Fysbis](https://attack.mitre.org/software/S0410) has used the command ls /etc | egrep -e"fedora\*|debian\*|gentoo\*|mandriva\*|mandrake\*|meego\*|redhat\*|lsb-\*|sun-\*|SUSE\*|release" to determine which Linux OS version is running.(Citation: Fysbis Palo Alto Analysis)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--834bbbc7-33b7-41e4-9bc8-98401a5a0e36`.
