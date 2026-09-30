---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0669"
target_object: "T1027.010"
stix_relationship_id: "relationship--d4c1ae1c-e258-4cce-9047-1557e1bdb680"
---
# Relationship 7981: S0669 — uses → T1027.010

**Source object:** [[01 ATT&CK/S0669 - KOCTOPUS|S0669: KOCTOPUS]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1027.010 - Command Obfuscation|T1027.010: Command Obfuscation]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[KOCTOPUS](https://attack.mitre.org/software/S0669) has obfuscated scripts with the BatchEncryption tool.(Citation: MalwareBytes LazyScripter Feb 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--d4c1ae1c-e258-4cce-9047-1557e1bdb680`.
