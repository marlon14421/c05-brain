---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0063"
target_object: "T1485"
stix_relationship_id: "relationship--c6986534-9705-42f2-baa7-66e760090e8a"
---
# Relationship 5045: C0063 — uses → T1485

**Source object:** [[01 ATT&CK/C0063 - 2025 Poland Wiper Attacks|C0063: 2025 Poland Wiper Attacks]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1485 - Data Destruction|T1485: Data Destruction]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

During the [2025 Poland Wiper Attacks](https://attack.mitre.org/campaigns/C0063), the adversaries utilized wiper malware to overwrite files using a 16-byte buffer that fully overwrites files 16 bytes or smaller or partially overwrites files greater than 16 bytes to speed up the process.(Citation: ESET DynoWiper JAN 2026)(Citation: ESET DynoWiper Update JAN 2026)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c6986534-9705-42f2-baa7-66e760090e8a`.
