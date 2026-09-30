---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0063"
target_object: "T1113"
stix_relationship_id: "relationship--b0b07276-d3d9-47ea-9fdd-412ed00325d9"
---
# Relationship 7301: C0063 — uses → T1113

**Source object:** [[01 ATT&CK/C0063 - 2025 Poland Wiper Attacks|C0063: 2025 Poland Wiper Attacks]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1113 - Screen Capture|T1113: Screen Capture]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

During the [2025 Poland Wiper Attacks](https://attack.mitre.org/campaigns/C0063), the adversaries captured screenshots of devices using nircmd console through the command nircmd.exe “savescreenshot C:\Windows\Temp\imagetmp.png .(Citation: CERT Polska)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--b0b07276-d3d9-47ea-9fdd-412ed00325d9`.
