---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0094"
target_object: "T1059.001"
stix_relationship_id: "relationship--c2379d5f-4d8d-4eaa-b966-bf31b227f5e3"
---
# Relationship 9439: G0094 — uses → T1059.001

**Source object:** [[01 ATT&CK/G0094 - Kimsuky|G0094: Kimsuky]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059.001 - PowerShell|T1059.001: PowerShell]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Kimsuky](https://attack.mitre.org/groups/G0094) has executed a variety of PowerShell scripts including Invoke-Mimikatz.(Citation: EST Kimsuky April 2019)(Citation: CISA AA20-301A Kimsuky)(Citation: Talos Kimsuky Nov 2021)(Citation: KISA Operation Muzabi)(Citation: Mandiant APT43 March 2024)(Citation: Aryaka Kimsuky July 2025) [Kimsuky](https://attack.mitre.org/groups/G0094) has also utilized PowerShell scripts for execution, persistence, and defense evasion.(Citation: Securonix Kimsuky February 2025) [Kimsuky](https://attack.mitre.org/groups/G0094) has leveraged PowerShell’s cmdlet `Expand-Archive` to extract contents of zip files into the same directory.(Citation: Aryaka Kimsuky July 2025) [Kimsuky](https://attack.mitre.org/groups/G0094) has employed ClickFix type tactics enticing victims to copy and paste malicious PowerShell commands and scripts, where the scripts ultimately led to [QuasarRAT](https://attack.mitre.org/software/S0262).(Citation: NaumaanProofpoint_GlobalClickFix_April2025)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c2379d5f-4d8d-4eaa-b966-bf31b227f5e3`.
