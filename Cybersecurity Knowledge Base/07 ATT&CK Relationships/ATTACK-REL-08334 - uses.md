---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0094"
target_object: "T1057"
stix_relationship_id: "relationship--ba7a0a7d-3a54-480f-86ce-f92d29dbabe1"
---
# Relationship 8334: G0094 — uses → T1057

**Source object:** [[01 ATT&CK/G0094 - Kimsuky|G0094: Kimsuky]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1057 - Process Discovery|T1057: Process Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Kimsuky](https://attack.mitre.org/groups/G0094) can gather a list of all processes running on a victim's machine.(Citation: Talos Kimsuky Nov 2021) [Kimsuky](https://attack.mitre.org/groups/G0094) has also obtained running processes on the victim device utilizing PowerShell cmdlet `Get-Process`.(Citation: Securonix Kimsuky February 2025)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--ba7a0a7d-3a54-480f-86ce-f92d29dbabe1`.
