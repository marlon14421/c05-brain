---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0063"
target_object: "T1059.004"
stix_relationship_id: "relationship--7d6c7fdf-2a63-44ac-b709-ea360c054513"
---
# Relationship 6309: C0063 — uses → T1059.004

**Source object:** [[01 ATT&CK/C0063 - 2025 Poland Wiper Attacks|C0063: 2025 Poland Wiper Attacks]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059.004 - Unix Shell|T1059.004: Unix Shell]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

During the [2025 Poland Wiper Attacks](https://attack.mitre.org/campaigns/C0063), the adversaries utilized the Linux `dd` command to overwrite portions of the disks with random data.(Citation: CERT Polska)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--7d6c7fdf-2a63-44ac-b709-ea360c054513`.
