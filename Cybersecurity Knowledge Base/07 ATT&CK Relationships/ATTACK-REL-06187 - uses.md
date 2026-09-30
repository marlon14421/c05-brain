---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1242"
target_object: "T1688"
stix_relationship_id: "relationship--d6c69c31-f292-4939-82e2-addbd84604e9"
---
# Relationship 6187: S1242 — uses → T1688

**Source object:** [[01 ATT&CK/S1242 - Qilin|S1242: Qilin]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1688 - Safe Mode Boot|T1688: Safe Mode Boot]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Qilin](https://attack.mitre.org/software/S1242) can reboot targeted systems in safe mode to avoid detection.(Citation: Trend Micro Agenda Ransomware AUG 2022)(Citation: BushidoToken Qilin RaaS JUN 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--d6c69c31-f292-4939-82e2-addbd84604e9`.
