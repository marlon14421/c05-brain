---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0129"
target_object: "T1678"
stix_relationship_id: "relationship--3426458d-9dcc-48b3-8bfc-24cf82377656"
---
# Relationship 8360: G0129 — uses → T1678

**Source object:** [[01 ATT&CK/G0129 - Mustang Panda|G0129: Mustang Panda]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1678 - Delay Execution|T1678: Delay Execution]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Mustang Panda](https://attack.mitre.org/groups/G0129) has delayed the execution of payloads leveraging ping echo requests `cmd /c ping 8.8.8.8 -n 70&&"%temp%\ "`.(Citation: Eset PlugX Korplug Mustang Panda March 2022)(Citation: Sophos PlugX September 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--3426458d-9dcc-48b3-8bfc-24cf82377656`.
