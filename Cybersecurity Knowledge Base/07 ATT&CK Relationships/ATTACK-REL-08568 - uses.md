---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1051"
target_object: "T1105"
stix_relationship_id: "relationship--7d0f57f6-6bed-44b2-a6b2-0e3da3e57f5e"
---
# Relationship 8568: G1051 — uses → T1105

**Source object:** [[01 ATT&CK/G1051 - Medusa Group|G1051: Medusa Group]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1105 - Ingress Tool Transfer|T1105: Ingress Tool Transfer]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Medusa Group](https://attack.mitre.org/groups/G1051) has leveraged [certutil](https://attack.mitre.org/software/S0160), PowerShell, and Windows Command to download additional tools to include RMM services.(Citation: CISA Medusa Group Medusa Ransomware March 2025) [Medusa Group](https://attack.mitre.org/groups/G1051) has also engaged in “Bring Your Own Vulnerable Driver” (BYOVD) and downloaded vulnerable or signed drivers to the victim environment to disable security tools.(Citation: CISA Medusa Group Medusa Ransomware March 2025)(Citation: Broadcom Medusa Ransomware Medusa Group March 2025)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--7d0f57f6-6bed-44b2-a6b2-0e3da3e57f5e`.
