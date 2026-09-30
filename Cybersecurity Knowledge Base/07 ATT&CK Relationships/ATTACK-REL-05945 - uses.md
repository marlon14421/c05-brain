---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0119"
target_object: "T1685.005"
stix_relationship_id: "relationship--ac9b186f-dfd1-4110-b53e-299652097280"
---
# Relationship 5945: G0119 — uses → T1685.005

**Source object:** [[01 ATT&CK/G0119 - Indrik Spider|G0119: Indrik Spider]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1685.005 - Clear Windows Event Logs|T1685.005: Clear Windows Event Logs]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Indrik Spider](https://attack.mitre.org/groups/G0119) has used [Cobalt Strike](https://attack.mitre.org/software/S0154) to empty log files.(Citation: Symantec WastedLocker June 2020) Additionally, [Indrik Spider](https://attack.mitre.org/groups/G0119) has cleared all event logs using `wevutil`.(Citation: Mandiant_UNC2165)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--ac9b186f-dfd1-4110-b53e-299652097280`.
