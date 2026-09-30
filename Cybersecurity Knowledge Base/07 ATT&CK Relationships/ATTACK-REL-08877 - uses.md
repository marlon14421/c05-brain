---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0015"
target_object: "T1030"
stix_relationship_id: "relationship--ca476de5-e17e-4011-9e5b-b438299c385c"
---
# Relationship 8877: C0015 — uses → T1030

**Source object:** [[01 ATT&CK/C0015 - C0015|C0015: C0015]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1030 - Data Transfer Size Limits|T1030: Data Transfer Size Limits]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

During [C0015](https://attack.mitre.org/campaigns/C0015), the threat actors limited [Rclone](https://attack.mitre.org/software/S1040)'s bandwidth setting during exfiltration.(Citation: DFIR Conti Bazar Nov 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--ca476de5-e17e-4011-9e5b-b438299c385c`.
