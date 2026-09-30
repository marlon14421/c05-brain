---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0040"
target_object: "T1596.005"
stix_relationship_id: "relationship--ba40c7b2-7f63-4976-9145-3b7f57f9c4cc"
---
# Relationship 8467: C0040 — uses → T1596.005

**Source object:** [[01 ATT&CK/C0040 - APT41 DUST|C0040: APT41 DUST]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1596.005 - Scan Databases|T1596.005: Scan Databases]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[APT41 DUST](https://attack.mitre.org/campaigns/C0040) used internet scan data for target development.(Citation: Google Cloud APT41 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--ba40c7b2-7f63-4976-9145-3b7f57f9c4cc`.
