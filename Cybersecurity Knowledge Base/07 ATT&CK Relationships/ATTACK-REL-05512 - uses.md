---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1181"
target_object: "T1068"
stix_relationship_id: "relationship--647eae34-69ab-4cc9-aa9e-44ff570d4fd2"
---
# Relationship 5512: S1181 — uses → T1068

**Source object:** [[01 ATT&CK/S1181 - BlackByte 2.0 Ransomware|S1181: BlackByte 2.0 Ransomware]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1068 - Exploitation for Privilege Escalation|T1068: Exploitation for Privilege Escalation]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[BlackByte 2.0 Ransomware](https://attack.mitre.org/software/S1181) exploits a vulnerability in the RTCore64.sys driver (CVE-2019-16098) to enable privilege escalation and defense evasion when run as a service.(Citation: Microsoft BlackByte 2023)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--647eae34-69ab-4cc9-aa9e-44ff570d4fd2`.
