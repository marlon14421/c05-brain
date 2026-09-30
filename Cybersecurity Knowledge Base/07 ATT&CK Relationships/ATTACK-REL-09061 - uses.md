---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0129"
target_object: "T1027.012"
stix_relationship_id: "relationship--f5d27f3c-743f-4867-8b18-8eda5527babe"
---
# Relationship 9061: G0129 — uses → T1027.012

**Source object:** [[01 ATT&CK/G0129 - Mustang Panda|G0129: Mustang Panda]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1027.012 - LNK Icon Smuggling|T1027.012: LNK Icon Smuggling]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Mustang Panda](https://attack.mitre.org/groups/G0129) has utilized LNK files to hide malicious scripts for execution.(Citation: Cisco Talos MUSTANG PANDA PLUGX PUBLOAD MAY 2022)(Citation: Sophos Mustang Panda PLUGX) [Mustang Panda](https://attack.mitre.org/groups/G0129) has also leveraged LNK files that were programmed to display a PDF icon to entice the victim to click on the file to execute an office.exe binary.(Citation: CSIRT CTI MUSTANG PANDA PUBLOAD TONESHELL JAN 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--f5d27f3c-743f-4867-8b18-8eda5527babe`.
