---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0034"
target_object: "T1588.002"
stix_relationship_id: "relationship--59116a0e-f23b-43ec-8b25-fbad5043344a"
---
# Relationship 5269: G0034 — uses → T1588.002

**Source object:** [[01 ATT&CK/G0034 - Sandworm Team|G0034: Sandworm Team]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1588.002 - Tool|T1588.002: Tool]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Sandworm Team](https://attack.mitre.org/groups/G0034) has acquired open-source tools for their operations, including [Invoke-PSImage](https://attack.mitre.org/software/S0231), which was used to establish an encrypted channel from a compromised host to [Sandworm Team](https://attack.mitre.org/groups/G0034)'s C2 server in preparation for the 2018 Winter Olympics attack, as well as [Impacket](https://attack.mitre.org/software/S0357) and RemoteExec, which were used in their 2022 [Prestige](https://attack.mitre.org/software/S1058) operations.(Citation: US District Court Indictment GRU Unit 74455 October 2020)(Citation: Microsoft Prestige ransomware October 2022) Additionally, [Sandworm Team](https://attack.mitre.org/groups/G0034) has used [Empire](https://attack.mitre.org/software/S0363), [Cobalt Strike](https://attack.mitre.org/software/S0154) and [PoshC2](https://attack.mitre.org/software/S0378).(Citation: mandiant_apt44_unearthing_sandworm)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--59116a0e-f23b-43ec-8b25-fbad5043344a`.
