---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0081"
target_object: "T1036.005"
stix_relationship_id: "relationship--0fd5d3bc-d736-43c0-b9ec-f1dcd95411a7"
---
# Relationship 9921: S0081 — uses → T1036.005

**Source object:** [[01 ATT&CK/S0081 - Elise|S0081: Elise]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1036.005 - Match Legitimate Resource Name or Location|T1036.005: Match Legitimate Resource Name or Location]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

If installing itself as a service fails, [Elise](https://attack.mitre.org/software/S0081) instead writes itself as a file named svchost.exe saved in %APPDATA%\Microsoft\Network.(Citation: Lotus Blossom Jun 2015)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--0fd5d3bc-d736-43c0-b9ec-f1dcd95411a7`.
