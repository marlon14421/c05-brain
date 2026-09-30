---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0001"
target_object: "T1027.010"
stix_relationship_id: "relationship--29883758-034d-4811-9145-9e12652edf66"
---
# Relationship 5487: C0001 — uses → T1027.010

**Source object:** [[01 ATT&CK/C0001 - Frankenstein|C0001: Frankenstein]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1027.010 - Command Obfuscation|T1027.010: Command Obfuscation]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

During [Frankenstein](https://attack.mitre.org/campaigns/C0001), the threat actors ran encoded commands from the command line.(Citation: Talos Frankenstein June 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--29883758-034d-4811-9145-9e12652edf66`.
