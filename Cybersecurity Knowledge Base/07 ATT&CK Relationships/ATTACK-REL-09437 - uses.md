---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0021"
target_object: "T1608.001"
stix_relationship_id: "relationship--895ab8e5-8f5f-420f-b283-61ee0d7ac37a"
---
# Relationship 9437: C0021 — uses → T1608.001

**Source object:** [[01 ATT&CK/C0021 - C0021|C0021: C0021]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1608.001 - Upload Malware|T1608.001: Upload Malware]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

For [C0021](https://attack.mitre.org/campaigns/C0021), the threat actors uploaded malware to websites under their control.(Citation: FireEye APT29 Nov 2018)(Citation: Microsoft Unidentified Dec 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--895ab8e5-8f5f-420f-b283-61ee0d7ac37a`.
