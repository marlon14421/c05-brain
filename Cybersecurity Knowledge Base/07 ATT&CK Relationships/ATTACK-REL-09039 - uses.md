---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0010"
target_object: "T1016"
stix_relationship_id: "relationship--9eefeafd-aca1-4e4c-8d29-ea6f9154808a"
---
# Relationship 9039: G0010 — uses → T1016

**Source object:** [[01 ATT&CK/G0010 - Turla|G0010: Turla]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1016 - System Network Configuration Discovery|T1016: System Network Configuration Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Turla](https://attack.mitre.org/groups/G0010) surveys a system upon check-in to discover network configuration details using the arp -a , nbtstat -n , net config , ipconfig /all , and route commands, as well as [NBTscan](https://attack.mitre.org/software/S0590).(Citation: Kaspersky Turla)(Citation: Symantec Waterbug Jun 2019)(Citation: ESET ComRAT May 2020) [Turla](https://attack.mitre.org/groups/G0010) RPC backdoors have also retrieved registered RPC interface information from process memory.(Citation: ESET Turla PowerShell May 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--9eefeafd-aca1-4e4c-8d29-ea6f9154808a`.
