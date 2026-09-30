---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1149"
target_object: "T1218.003"
stix_relationship_id: "relationship--0c45658b-2911-4b06-8b57-d34cc16d1e1d"
---
# Relationship 6422: S1149 — uses → T1218.003

**Source object:** [[01 ATT&CK/S1149 - CHIMNEYSWEEP|S1149: CHIMNEYSWEEP]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1218.003 - CMSTP|T1218.003: CMSTP]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[CHIMNEYSWEEP](https://attack.mitre.org/software/S1149) can use CMSTP.exe to install a malicious Microsoft Connection Manager Profile.(Citation: Mandiant ROADSWEEP August 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--0c45658b-2911-4b06-8b57-d34cc16d1e1d`.
