---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1129"
target_object: "T1490"
stix_relationship_id: "relationship--aeb5cdda-6344-4048-9b41-a0e0e75ef099"
---
# Relationship 7246: S1129 — uses → T1490

**Source object:** [[01 ATT&CK/S1129 - Akira|S1129: Akira]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1490 - Inhibit System Recovery|T1490: Inhibit System Recovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Akira](https://attack.mitre.org/software/S1129) will delete system volume shadow copies via PowerShell commands.(Citation: Kersten Akira 2023)(Citation: CISA Akira Ransomware APR 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--aeb5cdda-6344-4048-9b41-a0e0e75ef099`.
