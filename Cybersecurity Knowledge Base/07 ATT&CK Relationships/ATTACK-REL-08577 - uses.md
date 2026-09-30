---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0269"
target_object: "T1027.010"
stix_relationship_id: "relationship--7b5178ce-a9bc-405e-b062-22b4276fbf99"
---
# Relationship 8577: S0269 — uses → T1027.010

**Source object:** [[01 ATT&CK/S0269 - QUADAGENT|S0269: QUADAGENT]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1027.010 - Command Obfuscation|T1027.010: Command Obfuscation]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[QUADAGENT](https://attack.mitre.org/software/S0269) was likely obfuscated using `Invoke-Obfuscation`.(Citation: Unit 42 QUADAGENT July 2018)(Citation: GitHub Invoke-Obfuscation)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--7b5178ce-a9bc-405e-b062-22b4276fbf99`.
