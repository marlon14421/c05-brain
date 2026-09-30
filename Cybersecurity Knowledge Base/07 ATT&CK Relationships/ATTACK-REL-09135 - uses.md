---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0016"
target_object: "T1059.001"
stix_relationship_id: "relationship--7f78df2e-e6e9-43f1-815b-58e4a10fc594"
---
# Relationship 9135: G0016 — uses → T1059.001

**Source object:** [[01 ATT&CK/G0016 - APT29|G0016: APT29]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059.001 - PowerShell|T1059.001: PowerShell]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[APT29](https://attack.mitre.org/groups/G0016) has used encoded PowerShell scripts uploaded to [CozyCar](https://attack.mitre.org/software/S0046) installations to download and install [SeaDuke](https://attack.mitre.org/software/S0053).(Citation: Symantec Seaduke 2015)(Citation: Mandiant No Easy Breach)(Citation: ESET T3 Threat Report 2021)(Citation: Secureworks IRON HEMLOCK Profile)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--7f78df2e-e6e9-43f1-815b-58e4a10fc594`.
