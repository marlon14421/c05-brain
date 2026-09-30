---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0595"
target_object: "T1543.001"
stix_relationship_id: "relationship--979bd2a9-bc77-4741-bc79-0badc9e1e98c"
---
# Relationship 5720: S0595 — uses → T1543.001

**Source object:** [[01 ATT&CK/S0595 - ThiefQuest|S0595: ThiefQuest]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1543.001 - Launch Agent|T1543.001: Launch Agent]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[ThiefQuest](https://attack.mitre.org/software/S0595) installs a launch item using an embedded encrypted launch agent property list template. The plist file is installed in the ~/Library/LaunchAgents/ folder and configured with the path to the persistent binary located in the ~/Library/ folder.(Citation: wardle evilquest parti)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--979bd2a9-bc77-4741-bc79-0badc9e1e98c`.
