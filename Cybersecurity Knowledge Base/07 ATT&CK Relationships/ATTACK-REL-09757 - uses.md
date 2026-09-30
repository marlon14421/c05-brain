---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0129"
target_object: "T1564.001"
stix_relationship_id: "relationship--34b96e5d-1b2a-4ca5-89b5-7de398966bea"
---
# Relationship 9757: G0129 — uses → T1564.001

**Source object:** [[01 ATT&CK/G0129 - Mustang Panda|G0129: Mustang Panda]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1564.001 - Hidden Files and Directories|T1564.001: Hidden Files and Directories]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Mustang Panda](https://attack.mitre.org/groups/G0129)'s [PlugX](https://attack.mitre.org/software/S0013) variant has created a hidden folder on USB drives named RECYCLE.BIN to store malicious executables and collected data.(Citation: Avira Mustang Panda January 2020) [Mustang Panda](https://attack.mitre.org/groups/G0129) has also modified file attributes to `hidden` and `system`.(Citation: Eset PlugX Korplug Mustang Panda March 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--34b96e5d-1b2a-4ca5-89b5-7de398966bea`.
