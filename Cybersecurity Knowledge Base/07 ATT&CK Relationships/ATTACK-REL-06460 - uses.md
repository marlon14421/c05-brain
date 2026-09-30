---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1073"
target_object: "T1059.012"
stix_relationship_id: "relationship--395f4ec5-caaf-4cf5-9700-8033dcf81334"
---
# Relationship 6460: S1073 — uses → T1059.012

**Source object:** [[01 ATT&CK/S1073 - Royal|S1073: Royal]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059.012 - Hypervisor CLI|T1059.012: Hypervisor CLI]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

Royal ransomware uses `esxcli` to gather a list of running VMs and terminate them.(Citation: Trend Micro Royal Linux ESXi February 2023)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--395f4ec5-caaf-4cf5-9700-8033dcf81334`.
