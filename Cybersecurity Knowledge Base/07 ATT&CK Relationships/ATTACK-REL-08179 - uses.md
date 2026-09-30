---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0165"
target_object: "T1049"
stix_relationship_id: "relationship--8336111f-565e-4294-8b18-182c26da2421"
---
# Relationship 8179: S0165 — uses → T1049

**Source object:** [[01 ATT&CK/S0165 - OSInfo|S0165: OSInfo]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1049 - System Network Connections Discovery|T1049: System Network Connections Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[OSInfo](https://attack.mitre.org/software/S0165) enumerates the current network connections similar to net use .(Citation: Symantec Buckeye)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--8336111f-565e-4294-8b18-182c26da2421`.
