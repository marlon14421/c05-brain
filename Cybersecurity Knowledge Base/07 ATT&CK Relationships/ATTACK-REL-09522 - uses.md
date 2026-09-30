---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1242"
target_object: "T1069.002"
stix_relationship_id: "relationship--7ac60f16-6b9a-4226-af16-b486f5085f71"
---
# Relationship 9522: S1242 — uses → T1069.002

**Source object:** [[01 ATT&CK/S1242 - Qilin|S1242: Qilin]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1069.002 - Domain Groups|T1069.002: Domain Groups]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Qilin](https://attack.mitre.org/software/S1242) can run PowerShell cmdlets to discover domain groups.(Citation: Cisco Talos Qilin Ransomware OCT 2025)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--7ac60f16-6b9a-4226-af16-b486f5085f71`.
